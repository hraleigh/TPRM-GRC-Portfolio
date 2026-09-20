# Control crosswalk (portfolio sample)

A crosswalk maps the same control idea across frameworks so one
piece of vendor evidence can be cited more than one way. It is a
review aid for writing findings. It is not a complete certification
matrix, a HIPAA determination, or legal advice.

Skip the HIPAA column when the vendor does not handle health data.

| Domain | NIST CSF 2.0 | SOC 2 TSC | ISO 27001:2022 | HIPAA Security Rule |
|---|---|---|---|---|
| Inventory / scope | ID.AM | CC2.1 | A.5.9, A.8.9 | 164.308(a)(1) risk analysis scope |
| Governance / policy | GV.PO | CC1.2, CC5.3 | A.5.1, A.5.2 | 164.308(a)(1) security management |
| Access control | PR.AA | CC6.1–CC6.3 | A.5.15, A.5.18, A.8.2 | 164.312(a) access control |
| Privileged access | PR.AA | CC6.1, CC6.2 | A.8.2, A.8.3 | 164.308(a)(4) access management |
| Encryption in transit / at rest | PR.DS | CC6.1, CC6.7 | A.8.24 | 164.312(a)(2)(iv) encryption (addressable); 164.312(e) transmission |
| Logging / monitoring | DE.CM, DE.AE | CC7.2, CC7.3 | A.8.15, A.8.16 | 164.312(b) audit controls |
| Vulnerability management | ID.RA, PR.PS | CC7.1 | A.8.8 | 164.308(a)(1) risk management |
| Independent testing | ID.RA, DE.CM | CC4.1, CC7.1 | A.5.35, A.8.8 | 164.308(a)(8) evaluation |
| Incident response | RS.MA, RS.CO | CC7.3–CC7.5 | A.5.24–A.5.26 | 164.308(a)(6) incident procedures |
| BCP / DR | RC.RP | A1.2, A1.3 | A.5.29, A.5.30 | 164.308(a)(7) contingency plan |
| 4th parties / subprocessors | ID.SC | CC9.2 | A.5.19–A.5.22 | 164.308(b) business associate / contractor |
| HR screening / awareness | PR.AT | CC1.4, CC2.2 | A.6.1, A.6.3 | 164.308(a)(3), (a)(5) workforce / training |
| Retention / disposal / exit | PR.DS, GV.OV | CC6.5 | A.8.10, A.5.34 | 164.310(d) device and media controls |
| Privacy / minimization | GV.PO, PR.DS | P4–P8 if privacy TSC in scope | A.5.34 | Privacy Rule and minimum necessary if PHI |

## How to use in an assessment
1. Vendor answers the questionnaire.
2. Map each gap to a row above.
3. Cite the framework the business asked for.
4. Request evidence in that row instead of sending a new 200-question form.

## BCP note
For a Critical vendor, business continuity is in scope because
internal policy, SOC 2 availability, ISO continuity controls,
NIST recover, and (if ePHI) HIPAA contingency planning all point
at the same artifact: a BCP/DR plan with RTO/RPO and last test date.