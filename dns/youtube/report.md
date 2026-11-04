# Youtube DNS Maintenance Report

Generated: `2026-11-04T14:24:24Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 108 |
| Pending | 1 |
| Suspect | 0 |
| Quarantine | 1 |
| Excluded | 0 |
| Expired | 6 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 108 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **108**
Average stability: **99.3%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 3 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr1---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 7 | TIMEOUT | 74.125.8.166 | 73.1 | 26 |
| `rr2---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 7 | TIMEOUT | 74.125.8.167 | 85.1 | 47 |
| `rr3---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 7 | TIMEOUT | 74.125.8.168 | 63.2 | 19 |

## Discovery

Discovery state updated: `2026-11-04T14:24:24Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
