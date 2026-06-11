# 🔍 ISO/IEC 27001:2022 — Information Security Gap Analysis

> A professional GRC portfolio project demonstrating a structured gap analysis of an organisation's information security controls against ISO/IEC 27001:2022 requirements.

---

## 📌 Project Overview

This gap analysis assesses a fictional technology organisation (TechCorp Solutions Ltd) against the full ISO/IEC 27001:2022 standard — covering clauses 5–10 and Annex A controls.

It was developed to demonstrate practical GRC competency in:

- ISO 27001:2022 audit methodology
- Control gap identification and evidence requirements
- Risk-based prioritisation of remediation actions
- ISMS documentation and compliance reporting
- AI-specific information security considerations

---

## 🗂️ What's Inside

| Sheet | Description |
|---|---|
| **Cover Page** | Organisation details, scope, assessor, assessment date |
| **Assumptions & Scope** | Organisation profile, assessment scope, methodology, assumptions, and limitations — mirrors a real audit engagement |
| **Executive Summary** | Auto-calculated compliance scores + 9 key findings with severity ratings |
| **Gap Analysis** | 50 controls assessed — current state, gap, recommended action, evidence required |
| **Remediation Roadmap** | 28 prioritised actions organised into 5 monthly implementation phases |
| **How to Use** | Methodology guidance, evidence collection tips, interview preparation notes |

---

## 🏢 Fictional Organisation Profile

| Field | Detail |
|---|---|
| **Organisation** | TechCorp Solutions Ltd |
| **Industry** | Technology / SaaS |
| **Size** | ~500 employees across 3 offices (Toronto, London, Singapore) |
| **Revenue** | ~CAD $40M |
| **Environment** | Cloud-first (AWS primary, Azure secondary, Microsoft 365) |
| **AI Systems** | 3 in production — internal LLM chatbot, HR screening tool, fraud detection model |
| **Prior ISMS** | None — first-time gap analysis |
| **Standard** | ISO/IEC 27001:2022 |
| **Assessment Date** | June 2026 |

---

## 📐 Assessment Scope

### In Scope
- Cloud infrastructure — AWS, Azure, Microsoft 365
- On-premise server room — Toronto HQ
- Corporate endpoints — 520 managed devices
- Customer-facing SaaS platform and API
- AI-powered applications (LLM chatbot, HR screening, fraud detection)
- Third-party integrations — Salesforce, Workday, Stripe

### Key Assumptions
- No formal ISMS currently implemented
- No ISO 27001 certification previously attempted
- AI systems deployed in production without formal AI governance framework
- Employees using external AI tools (ChatGPT, Copilot) without formal guidance
- Assessment based on simulated interviews, document review, and evidence sampling

### Assessment Methodology
- Simulated stakeholder interviews (CISO, IT Manager, HR Director, Legal, Cloud Architect)
- Document review — policies, procedures, contracts, configurations
- Technical observation — access controls, logging, patch compliance
- Evidence sampling — training records, audit logs, patch reports

---

## 📋 Controls Assessed

### ISO 27001:2022 Clauses
- Clause 5 — Organisational Controls
- Clause 6 — Planning
- Clause 7 — Support
- Clause 8 — Operation
- Clause 9 — Performance Evaluation
- Clause 10 — Improvement

### Annex A Domains
- Information Security Policies (A.5.x)
- Human Resource Security (A.6.x)
- Physical Security (A.7.x)
- Access Control (A.8.x)
- Supplier Relationships (A.5.19–A.5.21)
- Incident Management (A.5.24–A.5.26)
- Compliance (A.5.31–A.5.34)
- Logging & Monitoring (A.8.15–A.8.16)
- Vulnerability Management (A.8.8)
- Malware Protection (A.8.7)
- Secure Development (A.8.28)

---

## 🔴 Key Findings Summary

### Critical Gaps (Immediate Action Required)

| Control | Finding |
|---|---|
| **6.1 / 8.2** | No formal risk assessment process or risk register — fundamental ISMS requirement absent |
| **9.2** | Internal audit programme never conducted — no systematic ISMS evaluation |
| **A.5.23** | No cloud security policy despite significant AWS/Azure/M365 usage |
| **A.8.12** | No DLP solution — sensitive data entering external AI tools unmonitored |

### Notable AI-Specific Gaps

| Control | Finding |
|---|---|
| **A.5.26** | No AI incident response playbook — no procedure for prompt injection, data poisoning, or model rollback |
| **A.5.10** | AUP does not cover AI tools — no guidance on acceptable use of ChatGPT, Copilot, etc. |
| **A.5.34** | AI data processing not included in ROPA — no DPIA conducted for AI systems processing personal data |
| **A.8.15** | AI system inputs/outputs not logged — no audit trail for AI decisions |

### Strengths Identified

| Control | Finding |
|---|---|
| **A.8.5** | MFA deployed on all cloud admin portals and VPN ✅ |
| **A.5.10** | AUP signed by all employees within last 12 months ✅ |

---

## 📊 Compliance Score Summary

| Status | Count |
|---|---|
| ✅ Compliant | ~8 |
| ⚠️ Partial | ~28 |
| ❌ Non-Compliant | ~14 |
| ➖ Not Applicable | 0 |
| **Total Assessed** | **50** |

> A ~16% full compliance score is realistic for an organisation conducting its first ISO 27001 gap analysis with no prior ISMS in place. The goal of a gap analysis isn't to show a high score — it's to honestly identify where the organisation stands and provide a credible roadmap to certification readiness.

---

## 🗓️ Remediation Roadmap Overview

| Phase | Timeline | Focus |
|---|---|---|
| **Month 1** | Immediate | Critical gaps — risk assessment, internal audit, cloud policy, DLP |
| **Month 2** | Short-term | High priority — IS policy review, threat intelligence, asset register, AUP update |
| **Month 3** | Short-term | High priority — AI IR playbook, supplier contracts, PAM, patch SLA |
| **Month 4** | Medium-term | Medium priority — role-based training, CMDB, SBOM, DPIAs |
| **Month 5+** | Ongoing | Low priority — communication plan, continual improvement register |

---

## 🛠️ Skills Demonstrated

- ISO 27001:2022 standard knowledge (clauses and Annex A)
- Real audit engagement structure (scope, assumptions, methodology)
- Gap analysis methodology and compliance scoring
- Evidence-based audit thinking
- Risk-based remediation prioritisation
- AI governance integration into traditional ISMS
- GRC documentation and reporting standards
- Microsoft Excel (dashboard design, formulas, conditional formatting)

---

## 📁 Files

```
📄 ISO27001_Gap_Analysis_v2.xlsx   — Full gap analysis workbook (6 sheets)
📄 README.md                       — This file
```

---

## 🔄 How This Connects to Other Portfolio Projects

| Project | Frameworks | What It Shows |
|---|---|---|
| [AI GRC Risk Register](../ai-grc-risk-register) | NIST CSF, ISO 27001, NIST AI RMF, EU AI Act | Risk identification and treatment |
| **ISO 27001 Gap Analysis** (this project) | ISO 27001:2022 | Audit methodology and compliance assessment |
| AI Vendor Risk Assessment *(coming soon)* | NIST AI RMF, ISO 42001, EU AI Act | Third-party AI risk management |

Together these projects demonstrate end-to-end GRC competency — from risk identification through compliance assessment to third-party risk management.

---

## 📚 References

- [ISO/IEC 27001:2022](https://www.iso.org/standard/27001)
- [ISO/IEC 27002:2022 — Security Controls Guidance](https://www.iso.org/standard/75652.html)
- [NIST SP 800-53 — Security and Privacy Controls](https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final)
- [EU AI Act](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:32024R1689)
- [GDPR](https://gdpr-info.eu/)
- [OWASP LLM Top 10](https://owasp.org/www-project-top-10-for-large-language-model-applications/)

---

## 👤 Author

**Dhanya Mary Sam**
Cybersecurity Professional | GRC & AI Governance Specialist
Greater Toronto Area, Canada

Certifications: CEH v13 | Security+ (In Progress)
Currently pursuing: ISO 27001 Foundation | CompTIA SecAI+ | ISO 42001 Foundation

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue)](https://www.linkedin.com/in/dhanya-m-sam)

---

*This project was created for portfolio and educational purposes. The organisation, findings, and scores described are fictional and illustrative only.*
