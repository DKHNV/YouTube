# Youtube DNS Maintenance Report

Generated: `2026-11-02T15:39:41Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 101 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 7 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 101 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **101**
Average stability: **99.7%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 2 | TIMEOUT | 74.125.8.166 | 90.5 | 21 |
| `rr2---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 2 | TIMEOUT | 74.125.8.167 | 95.9 | 49 |
| `rr3---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 2 | TIMEOUT | 74.125.8.168 | 85.7 | 14 |

## Discovery

Discovery state updated: `2026-11-02T15:39:41Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
