# Youtube DNS Maintenance Report

Generated: `2026-11-18T07:16:05Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 121 |
| Pending | 1 |
| Suspect | 0 |
| Quarantine | 9 |
| Excluded | 0 |
| Expired | 1 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 121 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **121**
Average stability: **99.9%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 4 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 1 | TIMEOUT | 172.217.132.198 | 97.0 | 33 |
| `rr2---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 1 | TIMEOUT | 172.217.132.199 | 96.6 | 29 |
| `rr4---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 1 | TIMEOUT | 172.217.132.201 | 97.0 | 33 |
| `rr5---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 1 | TIMEOUT | 172.217.132.202 | 96.8 | 31 |

## Discovery

Discovery state updated: `2026-11-18T07:16:05Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
