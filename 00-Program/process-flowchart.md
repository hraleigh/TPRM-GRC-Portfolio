# TPRM process flow

Two entry tracks merge after confidentiality is confirmed.

```mermaid
flowchart TD
  A[Track A: New vendor request] --> NDA[NDA / confidentiality]
  B[Track B: P&L unapproved spend] --> B2[Contact business owner and open intake]
  B2 --> NDA
  NDA --> VAQ[Vendor assessment questionnaire - inherent risk]
  VAQ --> SIGNOFF[InfoSec sign-off for Critical / High]
  SIGNOFF --> TIER{Tier}
  TIER -->|Low| L[Lightweight review]
  TIER -->|Medium| M[Security questionnaire plus evidence]
  TIER -->|High or Critical| H[IS assessment: questionnaire, evidence, site visit if required]
  L --> R[Residual risk decision]
  M --> R
  H --> R
  R -->|Reject or exit| X[Do not use / stop new use]
  R -->|Accept with CAPs| C[Contract, approved inventory, CAP tracker]
  R -->|Accept| I[Contract and approved inventory]
  C --> MON[Monitoring]
  I --> MON
  B2 -.->|Unremediated high unapproved spend| SM[Report to senior management]