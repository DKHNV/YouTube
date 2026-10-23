# Youtube DNS Maintenance Report

Generated: `2026-10-23T15:43:20Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 86 |
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
| Suspect | 1 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **86**
Average stability: **99.5%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 1 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-5hnednsz.googlevideo.com` | suspect | `2026-10-20T09:58:37Z` | 14 | TIMEOUT | 74.125.8.230 | 63.2 | 38 |

## Discovery

Discovery state updated: `2026-10-23T15:43:20Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
