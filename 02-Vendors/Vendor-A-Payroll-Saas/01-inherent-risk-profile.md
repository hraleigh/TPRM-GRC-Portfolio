# Inherent-risk profile
**Vendor (simulated):** Payline Workforce SaaS  
**Service:** Hosted payroll, timekeeping, and tax-filing platform  
**Track:** A — new vendor  
**Date:** 1 September 2026  
**Assessor:** TPRM (portfolio sample)

## Relationship
Payline processes employee names, SSNs, bank accounts, and pay data
for a mid-size workforce. Payline staff do not have network access
into the customer environment. Hosting is a named U.S. cloud region
with one payroll-print subprocessor.

## Inherent scoring

| Factor | Score | Rationale |
|---|---|---|
| Data | 3 | Employee PII and banking data |
| Access | 2 | Application access; no customer-network admin |
| Criticality | 2 | Payroll disruption hurts operations; not a core banking rail |
| 4th party / hosting | 2 | Known cloud host; one disclosed subprocessor |
| **Average** | **2.25** | **Medium** |

## Decision
Medium tier. Standard vendor security questionnaire plus assurance
artifacts. BCP/DR in scope because payroll is time-critical.
Information Security notified; formal Critical/High sign-off not
required at Medium under this sample methodology.

## Next step
Collect questionnaire, SOC 2 Type II, BCP/DR test evidence, and
insurance certificate.