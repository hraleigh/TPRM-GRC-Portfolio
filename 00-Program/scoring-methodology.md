# Inherent and residual scoring (simulated)

Simple 3-point model so ratings can be explained to business owners.
Not a licensed scoring product.

## Inherent risk

Score each factor 1 (Low), 2 (Medium), or 3 (High).

| Factor | 1 Low | 2 Medium | 3 High |
|---|---|---|---|
| Data | No sensitive data | Internal or limited PII | Customer PII, payment, or health data |
| Access | No system access | App / limited user access | Admin, production, or network access |
| Criticality | Easy to replace | Disruption would hurt a team | Outage would stop a core process |
| 4th party / hosting | On-prem or no subprocessor | Known cloud host | Multiple subprocessors or unclear hosting |

**Inherent score** = average of the four factors.

| Average | Inherent tier | Assessment depth |
|---|---|---|
| 1.0–1.4 | Low | Lightweight review |
| 1.5–2.4 | Medium | Vendor security questionnaire plus evidence |
| 2.5–3.0 | High | Full information-security assessment |

Critical / High require Information Security sign-off before due
diligence is treated as complete.

Critical vendors include business continuity in scope (BCP/DR with
RTO/RPO and last test date).

### Example — Vendor B (Northline Support Cloud)
Customer-support CRM with customer PII.

| Factor | Score | Why |
|---|---|---|
| Data | 3 | Customer PII; possible sensitive notes in tickets |
| Access | 2 | Vendor staff can view tickets / records |
| Criticality | 2 | Support channel; not a core payment rail |
| 4th party / hosting | 3 | Cloud SaaS with subprocessors |
| **Average** | **2.5** | **High** |

## Control effectiveness

After evidence review, rate the control environment:

| Rating | Meaning |
|---|---|
| Strong | Current SOC 2 Type II / ISO, few exceptions, MFA, encryption, clear IR |
| Adequate | Assurance present; gaps with acceptable CAPs |
| Weak | Missing assurance, material exceptions, or no CAP plan |

## Residual risk

| Inherent | Controls Strong | Controls Adequate | Controls Weak |
|---|---|---|---|
| Low | Low | Low | Medium |
| Medium | Low | Medium | High |
| High | Medium | High | High |

Residual High: do not onboard, or onboard only with time-bound CAPs
and documented business risk acceptance.

## CAP severity

| Severity | Example | Target close |
|---|---|---|
| High | No MFA on PII access; no SOC 2; no breach-notice term | 30 days |
| Medium | Expired pentest; incomplete subprocessor list; stale DR test | 60–90 days |
| Low | Policy wording gap; insurance certificate renewal | 90–180 days |

Past-due High CAPs escalate to the business owner and InfoSec.
TPRM does not freeze purchase orders as a CAP action.