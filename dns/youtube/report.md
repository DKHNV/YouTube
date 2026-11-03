# Youtube DNS Maintenance Report

Generated: `2026-11-03T14:03:26Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 106 |
| Pending | 0 |
| Suspect | 0 |
| Quarantine | 7 |
| Excluded | 0 |
| Expired | 0 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 106 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **106**
Average stability: **99.5%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 4 | TIMEOUT | 74.125.8.166 | 82.6 | 23 |
| `rr2---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 4 | TIMEOUT | 74.125.8.167 | 91.7 | 48 |
| `rr3---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 4 | TIMEOUT | 74.125.8.168 | 75.0 | 16 |

## Discovery

Discovery state updated: `2026-11-03T14:03:26Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
