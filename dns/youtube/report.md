# Youtube DNS Maintenance Report

Generated: `2026-11-19T07:15:24Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 124 |
| Pending | 2 |
| Suspect | 0 |
| Quarantine | 9 |
| Excluded | 0 |
| Expired | 1 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 124 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **124**
Average stability: **99.7%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 4 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 3 | TIMEOUT | 172.217.132.198 | 90.6 | 32 |
| `rr2---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 3 | TIMEOUT | 172.217.132.199 | 90.3 | 31 |
| `rr4---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 3 | TIMEOUT | 172.217.132.201 | 90.6 | 32 |
| `rr5---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 3 | TIMEOUT | 172.217.132.202 | 90.6 | 32 |

## Discovery

Discovery state updated: `2026-11-19T07:15:24Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
