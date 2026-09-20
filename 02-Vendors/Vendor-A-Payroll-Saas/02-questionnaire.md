# Vendor assessment questionnaire
**Vendor:** Payline Workforce SaaS  
**Tier:** Medium  
**Data:** Employee PII and payroll / bank data  
**Package:** NDA confirmed. Standard questionnaire + SOC 2 / BCP.
CAIQ or SIG not required at Medium in this sample model.

| ID | Question | Domain | Requested evidence | Simulated answer |
|---|---|---|---|---|
| Q01 | What employee data do you store or process? | Data inventory | Data inventory | Name, SSN, bank account, pay history |
| Q02 | Where is data hosted, and which subprocessors can access it? | Hosting / 4th party | Architecture + subprocessor list | U.S. region; one print vendor |
| Q03 | Is access role-based and reviewed at least quarterly? | Access control | Access policy; sample review | Yes — quarterly review |
| Q04 | Is MFA required for all admin and staff access to payroll data? | Access control | Auth standard | Yes |
| Q05 | Are privileged accounts separate from day-to-day users and logged? | Privileged access | Privileged-access procedure | Yes |
| Q06 | Is employee data encrypted in transit and at rest? | Encryption | SOC 2 CC6 / encryption standard | Yes — attested in SOC 2 |
| Q07 | What controls limit bulk export of payroll files? | DLP | Export-control description | Role-based export; logged |
| Q08 | Retention period and deletion / return at contract end? | Retention / exit | Retention procedure | 7-year tax retention; deletion on exit after legal hold |
| Q09 | Current SOC 2 Type II or ISO 27001 covering this service? | Assurance | SOC 2 Type II | SOC 2 Type II current; no qualified opinion |
| Q10 | Any SOC 2 exceptions related to payroll processing? | Assurance quality | SOC 2 exception section | None material |
| Q11 | Annual independent pentest of this application? | Testing | Pentest attestation | Yes — current year |
| Q12 | Vulnerability scanning and severity SLAs? | Vuln mgmt | Vuln policy | Yes |
| Q13 | Logging of access to employee PII / bank data? | Logging | Logging standard | Yes |
| Q14 | Incident response and customer notification timeline? | IR | IR policy | Notify within 72 hours of confirmed breach |
| Q15 | Are subprocessors with payroll-data access assessed? | 4th party | Subprocessor TPRM summary | Print vendor assessed annually |
| Q16 | Background checks and annual security training? | People | HR / awareness policy | Yes |
| Q17 | BCP/DR with stated RTO/RPO, and date of last test? | Resilience | BCP summary + test date | RTO 24h / RPO 4h; last test 18 months ago |
| Q18 | Accept breach notice, audit rights, and data-deletion terms? | Contract | Security schedule | Standard terms accepted |
| Q19 | Cyber insurance in force? | Transfer | COI | Yes |
| Q20 | Can free-text payroll tickets contain extra sensitive data? How is that limited? | Minimization | Ticket-handling note | SSN masked in tickets |