# Findings memo — Payline Workforce SaaS
**Tier:** Medium  
**Inherent:** Medium  
**Residual (proposed):** Medium until CAP-004 closes, then Low

## Finding 1 — Stale DR test
**Severity:** Medium  
**Linked risk:** VR-005  
**Linked CAP:** CAP-004  
Payroll is time-critical. BCP states RTO 24 hours / RPO 4 hours, but
the last test is 18 months old. SOC 2 encryption and access control
are attested. Resilience evidence is the gap.

**Required action:** Run a DR test and send dated results with RTO/RPO
achieved. Due 30 October 2026.

## What is not a finding
SOC 2 Type II current, no qualified opinion. MFA attested. Encryption
in transit and at rest attested. Subprocessor disclosed.