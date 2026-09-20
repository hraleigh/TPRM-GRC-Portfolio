# TPRM / GRC portfolio

Sample third-party risk management files for analyst-level work:
vendor profiling, assessment questionnaires, control crosswalks,
findings, CAP tracking, and leadership reporting.

All vendors and evidence in this repository are simulated.
No employer documents or real personal data are included.

## What this demonstrates
- Inherent-risk profiling and Critical / High / Medium / Low tiering
- Vendor assessment questionnaires and evidence requests
- Mapping findings to NIST CSF, SOC 2, ISO 27001, and HIPAA Security Rule concepts
- Residual risk, corrective action plans, and closure evidence
- Inventory hygiene when unapproved supplier spend appears on the P&L
- Short operational notes and a leadership update

## How to read this repo
1. `00-program` — lifecycle, process flow, and scoring
2. `01-crosswalks` — questionnaire items to control frameworks
3. `02-vendors` — two worked assessments
4. `03-risk-register` — risk register and CAP tracker
5. `04-reporting` — monthly dashboard notes and leadership update
6. `05-templates` — blank forms

## Simulated vendors
| Folder | Vendor | Data | Inherent tier |
|---|---|---|---|
| `vendor-a-payroll-saas` | Payline Workforce SaaS | Employee / payroll data | Medium |
| `vendor-b-customer-support-crm` | Northline Support Cloud | Customer PII in tickets | High |

High-tier cloud vendors would also receive a standard control questionnaire such as CAIQ or SIG. Those workbooks are not copied here.

## Process in brief
Two entry tracks merge at the vendor assessment questionnaire:

- **New vendor** — intake → confidentiality / NDA → inherent-risk questionnaire → InfoSec sign-off for Critical/High → security assessment (site visit if confidential data is offsite) → residual decision → inventory and CAPs
- **Unapproved spend** — P&L review → contact the business → same assessment path. TPRM does not freeze purchase orders. Unremediated high unapproved spend is reported to senior management.

## Disclaimer
Framework mappings are a review aid for writing findings. They are not a certification, a HIPAA determination, or legal advice.
