# Youtube DNS Maintenance Report

Generated: `2026-10-10T16:13:34Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 71 |
| Pending | 1 |
| Suspect | 0 |
| Quarantine | 6 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 71 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **71**
Average stability: **99.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-gxuo03g-vqnl.googlevideo.com` | alive | `2026-10-10T16:13:34Z` | 1 | TIMEOUT | 87.245.222.236 | 97.9 | 48 |
| `rr2---sn-gxuo03g-vqnl.googlevideo.com` | alive | `2026-10-10T16:13:34Z` | 1 | TIMEOUT | 87.245.222.237 | 97.9 | 48 |

## Discovery

Discovery state updated: `2026-10-10T16:13:34Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
