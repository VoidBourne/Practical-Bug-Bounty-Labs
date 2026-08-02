# Practical-Bug-Bounty-Labs

Vulnerability reports documenting hands-on web application security labs.

## About

Each report in this repo follows a client-facing pentest report format: scope, methodology, findings with severity and impact, step-by-step reproduction with evidence, and remediation recommendations, rather than a raw technical writeup. The goal is to practice communicating findings the way they'd be delivered on a real engagement.

## Structure

Each folder contains a full report for one lab, including methodology, steps to reproduce, evidence, and remediation.

## Labs

| Lab | Vulnerability | 
|---|---|
| Auth 0x01 | Password Brute Force | [Report](./Auth_0x01_Report.pdf) |
| Auth 0x02 | MFA Bypass via Parameter Tampering | [Report](./Auth-0x02-MFA-Bypass/) |

## Testing scope and limitations

These labs were tested against specific vulnerability classes covered by the course material at the time each report was written, not a full security assessment. Findings reflect what was actively being learned and tested for; other vulnerabilities may be present in these applications that were out of scope for a given lab. This mirrors real engagements, where testing is always bounded by an agreed scope, but it's worth stating plainly here since these are self-directed labs rather than a client-defined scope of work.

## Tools used

ffuf, Burp Suite, browser developer tools

## Note

Lab environments used in these reports are from TCM Security's Practical Bug Bounty course. All findings, testing, and reporting were performed independently.
