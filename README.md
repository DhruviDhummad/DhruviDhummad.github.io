# Web Application Security Assessment – Talentin

This repository documents an **authorized internal web application security assessment**
of app.talentin.ai conducted as part of security learning and improvement efforts.

The assessment focuses on identifying common web security misconfigurations and risks
using industry-standard tools and methodologies.

---

## Scope
- Target: app.talentin.ai
- Testing type: Passive and low-impact testing
- Focus areas:
  - HTTP security headers
  - Authentication and session handling
  - Input validation (non-destructive)

Out-of-scope activities include denial-of-service, data destruction,
and aggressive automated exploitation.

---

## Methodology
The assessment follows structured security testing practices aligned with
:contentReference[oaicite:0]{index=0} Top 10 principles.

Each finding includes:
- Tested endpoint
- Tool used
- Evidence (screenshots)
- Risk assessment
- Remediation recommendation

Detailed testing steps are documented in the `methodology/` directory.

---

## Tools Used
- Burp Suite – HTTP interception and response analysis
- Kali Linux – Security testing environment
- Browser Developer Tools

---

## Repository Structure
- `methodology/` – Detailed test cases and findings
- `reports/` – Executive-level summaries
- `screenshots/` – Evidence collected during testing
- `authorization.md` – Statement of testing authorization
- `scope.md` – Defined testing boundaries

---

## Disclaimer
This assessment was performed **with authorization** and is intended
for educational and internal security improvement purposes only.
