BreachLine
Cybersecurity Investigation & Threat Analysis Platform

BreachLine is a browser-based learning project for documenting suspected security incidents, recording evidence and chain-of-custody events, tracking investigation activity, and preparing incident reports.
Features
- Phishing indicator checklist and transparent risk scoring (training aid only)
- Case details and status dashboard with documentation progress
- Evidence register with collection details, handling history, importance flags, and soft removal/restoration
- Removal preserves the evidence record and adds a custody-history event instead of silently deleting history
- Chronological investigation timeline
- Investigator notes and incident report generation
- Save report as HTML or print / save as PDF
- Browser-local workspace persistence and JSON backup import/export
- Malware, credential, and network incident documentation panels
Run locally
1. Download the HTML file.
2. Open it in a modern browser (Safari, Chrome, or Firefox).
3. Create a case, then document findings and evidence.
4. Use Export Case Backup regularly to save a portable JSON backup.
Important limitations
- This is a local browser-based documentation tool, not a SIEM, endpoint scanner, malware sandbox, or forensic acquisition suite.
- BreachLine does not visit or verify suspicious URLs and does not execute or scan files.
- Risk scoring is a training aid and does not independently establish whether an incident is malicious.
- Data saved in browser storage can be lost if browser data is cleared. Export backups and store them securely.
- Evidence removal is a soft removal from the active register; it intentionally preserves the historical record.
- Do not put real sensitive personal, employer, or incident data into a public repository or screenshots. Use sanitized demonstration cases.
Suggested GitHub screenshots
Capture a sanitized demo case showing: (1) the dashboard, (2) the phishing analysis and score, (3) evidence with custody history, and (4) the investigation timeline and generated report. Do not include real names, email addresses, government documents, account identifiers, or other personal data.
Project talking points
- Designed a client-side incident documentation workflow.
- Implemented local persistence and portable JSON backup/restore.
- Built evidence lifecycle controls that preserve custody history.
- Used DOM rendering and text-safe insertion for user-provided investigation content.
- Identified limitations clearly: the tool documents analyst inputs but does not independently verify threats.
License
Add a license before inviting reuse; do not imply a license has been granted unless you choose one.
