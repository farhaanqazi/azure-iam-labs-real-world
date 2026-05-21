# Azure IAM Labs — Identity & Access (Entra ID) + Data Analytics

Hands-on Microsoft Entra ID (Azure AD) labs built around real compliance-heavy
scenarios (NHS, banking). Each lab ships **two layers**:

- **Control layer** — the IAM configuration (the SC-300 skill set).
- **Data layer** — measuring and reporting it with **KQL** and **Power BI** (the edge most
  IAM practitioners lack).

Positioning: *securing **and** measuring access — not just configuring controls, but
proving they work to an auditor.*

## Labs

| # | Business problem | Control layer | Data layer |
|---|---|---|---|
| [1](lab1-block-risky-signins/) | Block risky sign-ins to patient data | Conditional Access + MFA, sign-in risk | KQL on `SigninLogs` — risky logins caught, policy verdicts |
| 2 | Emergency admin without standing privilege | PIM (JIT, time-boxed roles) | KQL on `AuditLogs` — who activated admin, when, why |
| 3 | Quarterly access certification | Entitlement Mgmt + Access Reviews | Power BI — dormant accounts, over-privilege, toxic combos |
| 4 | Joiner/mover/leaver automation | Microsoft Graph API + PowerShell | ETL: CSV → Graph + reconciliation report |
| 5 | Detect anomalous sign-ins | Entra ID Protection (risk policies) | KQL + Power BI exec dashboard — risk trends, MFA coverage |

## Skills demonstrated
Conditional Access · PIM · Access Reviews · Entitlement Management · Entra ID Protection ·
Microsoft Graph · KQL · Log Analytics · Power BI · PowerShell · identity governance (IGA).

## Tooling
Microsoft Entra ID (P2) · Azure Log Analytics · Microsoft Graph PowerShell · Azure CLI.
