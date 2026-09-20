# Findings memo — Northline Support Cloud
**Tier:** High  
**Inherent:** High  
**Residual (proposed):** High until CAP-001 closes

## Finding 1 — MFA not enforced on all PII roles
**Severity:** High  
**VR-001 / CAP-001**  
Support roles can open customer tickets without MFA. Customer PII
is in scope. SOC 2 is current but does not close this operational gap.

**Action:** Enforce MFA on all workforce and admin accounts with
ticket or PII access. Evidence: auth standard plus implementation
proof. Due 1 October 2026.

## Finding 2 — Incomplete subprocessor list
**Severity:** Medium  
**VR-002 / CAP-002**  
Fourth-party PII access cannot be assessed from the list provided.

**Action:** Complete subprocessor list stating which parties can
access customer PII. Due 1 November 2026.

## Finding 3 — Pentest attestation stale
**Severity:** Medium  
**VR-003 / CAP-003**  
Independent test letter is older than 12 months.

**Action:** Current pentest attestation for this service.
Due 1 December 2026.

## Not a finding
SOC 2 Type II with no qualified opinion. Encryption attested.
BCP tested within 12 months.