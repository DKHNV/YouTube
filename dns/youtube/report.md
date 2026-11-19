# Youtube DNS Maintenance Report

Generated: `2026-11-19T20:28:50Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 126 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 9 |
| Excluded | 0 |
| Expired | 1 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 126 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **126**
Average stability: **99.6%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 4 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 4 | TIMEOUT | 172.217.132.198 | 87.5 | 32 |
| `rr2---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 4 | TIMEOUT | 172.217.132.199 | 87.5 | 32 |
| `rr4---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 4 | TIMEOUT | 172.217.132.201 | 87.5 | 32 |
| `rr5---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 4 | TIMEOUT | 172.217.132.202 | 87.5 | 32 |

## Discovery

Discovery state updated: `2026-11-19T20:28:50Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
