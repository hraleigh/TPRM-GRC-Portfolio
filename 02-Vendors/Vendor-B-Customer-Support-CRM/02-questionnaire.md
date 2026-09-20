# Vendor assessment questionnaire
**Vendor:** Northline Support Cloud  
**Tier:** High  
**Data:** Customer PII in CRM / tickets  

| ID | Question | Domain | Maps to | Requested evidence | Simulated answer |
|---|---|---|---|---|---|
| Q01 | Do you store our customer PII? List elements. | Data inventory | SOC 2 CC2 / NIST ID.AM | Data inventory | Name, address, phone, email, member ID; ticket text |
| Q02 | Where is PII stored and which subprocessors can access it? | Residency / 4th party | CC9 / ID.SC | Architecture; subprocessor list | Multi-region cloud; list incomplete (two hosts unnamed) |
| Q03 | Is production PII access role-based and reviewed quarterly? | Access | CC6 / PR.AA | Access policy | Yes for admins; support-role review informal |
| Q04 | Is MFA required for all workforce and admin access to PII? | Access | CC6 / PR.AA | Auth standard | MFA on admins only; not all support roles |
| Q05 | Privileged accounts separate and logged? | Privileged access | CC6 / PR.AA | Privileged-access procedure | Yes |
| Q06 | PII encrypted in transit and at rest? | Encryption | CC6 / PR.DS | Encryption standard | Yes — SOC 2 |
| Q07 | Controls on bulk export / download of PII? | DLP | CC6 / PR.DS | Export controls | Exports allowed for team leads; logged |
| Q08 | Retention and deletion / return at exit? | Retention | CC6 / PR.DS | Retention procedure | 3 years; deletion on written request |
| Q09 | Current SOC 2 Type II and/or ISO 27001? | Assurance | CC4 / ISO | SOC 2 / ISO cert | SOC 2 Type II current; no ISO |
| Q10 | Qualified opinion or high-severity SOC exceptions? | Assurance quality | CC4 | SOC 2 exceptions | No qualified opinion |
| Q11 | Annual independent pentest of this application? | Testing | CC7 / ID.RA | Pentest letter | Last letter 16 months old |
| Q12 | Vuln scan and severity SLA? | Vuln mgmt | CC7 / ID.RA | Vuln policy | Yes |
| Q13 | Logging of access to customer PII? | Logging | CC7 / DE.CM | Logging standard | Yes for admin; ticket-view logs retained 30 days |
| Q14 | IR process and customer notification timeline? | IR | CC7 / RS | IR policy | Notify “without undue delay”; no hour SLA |
| Q15 | Subprocessors with PII access assessed? | 4th party | CC9 / ID.SC | Subprocessor TPRM | Incomplete list |
| Q16 | Background checks and annual training? | People | CC1 / PR.AT | HR policy | Yes |
| Q17 | BCP/DR with RTO/RPO and last test date? | Resilience | A1 / RC.RP | BCP + test | RTO 8h / RPO 1h; tested 8 months ago |
| Q18 | Contract: breach notice, audit rights, deletion? | Contract | CC9 | DPA / security schedule | Willing to accept standard terms |
| Q19 | Cyber insurance? | Transfer | — | COI | Yes |
| Q20 | How are extra-sensitive notes in tickets restricted? | Minimization | CC6 / PR.DS | Ticket-handling / masking | No field-level mask; policy asks agents not to paste SSNs |