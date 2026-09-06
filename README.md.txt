# Member 3 — OWASP ZAP Dynamic Scan  Part of: OWASP Top 10 Assessment Toolkit for a Restaurant Chain  
## What this covers A DAST (dynamic application security testing) pass using OWASP ZAP 2.17.0 against an authorized lab target (OWASP Juice Shop, run locally). Produces 6 documented findings with severity, evidence, and remediation.  
## Tool OWASP ZAP 2.17.0 — Automated Scan (traditional + AJAX spider) followed by an Active Scan.  
## Lab target OWASP Juice Shop, http://127.0.0.1:3000, run in an isolated local VM. No live or production system was tested.  
## Contents of this folder - /screenshots — evidence for each finding - /report — this mini-report (PDF/DOCX) - README.md — this file  
## Key findings SQL Injection (High); CSP misconfiguration, missing anti-clickjacking header, permissive CORS (Medium x3); private IP disclosure, application error disclosure (Low x2).  
## Disclaimer All testing was performed exclusively against an intentionally vulnerable, self-hosted training application. No unauthorized systems were accessed or tested.