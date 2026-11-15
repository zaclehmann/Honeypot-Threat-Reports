# Honeypot-Threat-Reports
Monthly threat intelligence reports and incident case studies from an internet-facing honeypot sensor in Australia. Findings, defences and indicators of compromise (attacker IPs, malware hashes). Shared under TLP:CLEAR.

## Reports

| Published | Covers | Report | Highlights |
|---|---|---|---|
| November 2026 | October 2026 | [Honeypot Threat Report: November 2026](reports/2026/11-November/honeypot-threat-report-2026-11.pdf) | Remote Desktop (RDP) is the single most hammered service. Weak passwords are still the whole game for SSH and Telnet. Once 'in', attackers moved fast |

## Case studies

Write-ups of individual incidents the sensor recorded.

| Published | Incident | Report | Highlights |
|---|---|---|---|
| November 2026 | 14–15 November 2026 | [Anatomy of an RDP Flood](case-studies/2026/11-November/rdp-flood-case-study-2026-11.pdf) | 16 hours, 20 million events, 0 login attempts. Eight consecutive servers in one /29 block flooded the RDP decoy with 469,373 connections. A quieter password attack ran alongside it |
