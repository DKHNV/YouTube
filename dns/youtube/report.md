# Youtube DNS Maintenance Report

Generated: `2026-10-22T15:51:49Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 85 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 6 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 85 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **85**
Average stability: **99.6%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-5hnednsz.googlevideo.com` | alive | `2026-10-20T09:58:37Z` | 10 | TIMEOUT | 74.125.8.230 | 70.6 | 34 |

## Discovery

Discovery state updated: `2026-10-22T15:51:49Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
