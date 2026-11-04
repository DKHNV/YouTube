# Youtube DNS Maintenance Report

Generated: `2026-11-04T23:37:29Z`

## DNS lifecycle

| State | Hosts |
|---|---:|
| Active | 109 |
| Pending | 2 |
| Suspect | 0 |
| Quarantine | 1 |
| Excluded | 0 |
| Expired | 6 |

## HTTPS/TLS observation

| State | Hosts |
|---|---:|
| Alive | 109 |
| Unknown | 0 |
| Suspect | 0 |
| Dead | 0 |

## Stability window

The score is based on measured HTTPS/TLS checks within the configured calendar-day window. SKIPPED observations are excluded.

Measured hosts: **109**
Average stability: **99.2%**

## Current HTTPS/TLS failures

| Type | Hosts |
|---|---:|
| TIMEOUT | 2 |

### Failure details

| Hostname | State | Since | Observations | Last error | IPv4 | Stability | Samples |
|---|---|---|---:|---|---|---:|---:|
| `rr2---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 8 | TIMEOUT | 74.125.8.167 | 82.6 | 46 |
| `rr3---sn-5hne6n6l.googlevideo.com` | alive | `2026-11-02T05:54:26Z` | 8 | TIMEOUT | 74.125.8.168 | 60.0 | 20 |

## Discovery

Discovery state updated: `2026-11-04T23:37:29Z`

## Notes

- Public active DNS file: `YouTube_DNS`.
- DNS lifecycle is time-based and does not depend on how many times per day the workflow runs.
- Hostname policy exclusions are semantic decisions and are tracked separately from DNS quarantine.
- HTTPS/TLS health is observational and never removes a hostname from the public DNS file.
