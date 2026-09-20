# TPRM lifecycle — two entry tracks

Simulated financial-services operating model for a portfolio.
Not a client or employer document.

Two ways a vendor enters the process. They merge at the vendor
assessment questionnaire.

## Track A. New vendor (planned onboarding)

1. **Intake**  
   Business owner requests a new vendor or a new use case.
   Check the approved inventory so a duplicate file is not opened.
   Capture service description, data types, access, users, and
   target go-live date.

2. **Confidentiality**  
   Confirm an NDA or MSA confidentiality clause before collecting
   SOC reports, architecture detail, or a full security questionnaire.
   If none exists, Procurement issues an NDA.

3. **Vendor assessment questionnaire (inherent risk / criticality)**  
   Profile the relationship: data sensitivity, system access,
   operational criticality, hosting, and subcontractors.
   Output: Critical, High, Medium, or Low. That tier sets
   assessment depth.

4. **Information Security sign-off**  
   Critical and High ratings require InfoSec sign-off (in a large
   bank, a Business ISO or geographic ISO) before due diligence
   is treated as complete. Vendor Management prepares the package.
   InfoSec owns the inherent-risk decision.

5. **Due diligence**  
   Depth follows tier:
   - Low: lightweight review
   - Medium: vendor security questionnaire plus assurance artifacts
   - High / Critical: information-security assessment —
     questionnaire, evidence, and a site visit when confidential
     data is stored, processed, or accessed offsite

   High-tier cloud / SaaS packets often include CAIQ or SIG, plus
   SOC 2 Type II, ISO 27001, pentest attestation, BCP/DR,
   insurance, and a subprocessor list. Critical vendors include
   business continuity (RTO/RPO and last test date) in scope.

   Vendor Management coordinates intake, scheduling, document
   collection, and issue tracking. Information Security leads the
   technical review and any on-site assessment.

6. **Residual risk and decision**  
   Rate residual risk after controls and contract terms.
   Recommend onboard, onboard with CAPs, or reject.

7. **Contract and inventory**  
   Confirm security, privacy, audit rights, breach notice, and
   exit language. Load vendor profile, tier, assessment, and
   issues into the system of record. Go-live waits for sign-off
   unless policy allows a documented exception.

8. **CAPs, monitoring, offboarding**  
   Track corrective actions to closure with evidence.
   Reassess by tier, or sooner after a breach, material assurance
   exception, ownership change, or new data use.
   On exit: remove access, confirm data return or deletion,
   update inventory.

## Track B. Unapproved supplier spend (found on the P&L)

1. Vendor Management reviews P&L / accounts payable for payees
   that are not on the approved list, or that are approved only
   for a different service or data use.

2. Contact the business owner. The relationship is unapproved
   and must go through Track A, or spend must move to an
   already approved supplier.

3. Open an intake and run the same path: confidentiality →
   vendor assessment questionnaire → InfoSec sign-off →
   security assessment by tier → residual decision → inventory.

4. TPRM does not freeze purchase orders, cancel contracts, or
   revoke system access.

5. Close the exception only when inventory status is Approved
   or Terminated.

6. If a business unit keeps a high level of unapproved spend
   and does not remediate, Vendor Management reports that to
   senior management. Senior management addresses it with the
   business. That is a management issue, not a TPRM
   containment action.

## Merge point

Tracks A and B use the same questionnaire, InfoSec sign-off,
security assessment, CAP, and monitoring process. Track B is
late: residual risk is often higher because the service may
already be live.