# Youtube DNS Maintenance Report

Generated: `2026-11-18T20:25:26Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 122 |
| Pending | 2 |
| Suspect | 0 |
| Quarantine | 9 |
| Excluded | 0 |
| Expired | 1 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 122 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **122**
Average stability: **99.8%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 4 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 2 | TIMEOUT | 172.217.132.198 | 93.9 | 33 |
| `rr2---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 2 | TIMEOUT | 172.217.132.199 | 93.3 | 30 |
| `rr4---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 2 | TIMEOUT | 172.217.132.201 | 93.9 | 33 |
| `rr5---sn-5hnednss.googlevideo.com` | alive | `2026-11-18T07:16:05Z` | 2 | TIMEOUT | 172.217.132.202 | 93.8 | 32 |

## Discovery

Discovery state updated: `2026-11-18T20:25:26Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
