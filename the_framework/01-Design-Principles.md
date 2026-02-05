# CHARM Design Principles

The **Cybersecurity Human Awareness & Risk Management (CHARM)** framework is guided by six foundational principles derived from the synthesis of the reviewed literature and ENISA’s behavioural cybersecurity guidance. Each principle shapes how human-related risk is identified, assessed, treated, measured, and governed.

---

## 1. Human-as-Asset Perspective

**Definition:** CHARM conceptualises humans as adaptive security resources whose behaviour can enhance organisational resilience when appropriately supported, rather than as inherent vulnerabilities to be controlled.

**Rationale:** The “weakest link” narrative is not only inaccurate—human factors form a socio-technical system—but counterproductive. ENISA’s evidence-based reviews stress that enabling secure behaviour through organisational design, usability, and support is more effective than threat-based messaging or punitive controls. When people are skilled, trusted, and supported, they can act as an adaptive defence layer and respond effectively to novel threats (e.g. “security heroism” in safety research). This principle shifts the focus from fixing the human to fixing the context in which they work.

---

## 2. Behaviour-Centred Security

**Definition:** The framework prioritises observed behaviour in real operational contexts over formal compliance with policies or self-reported intentions.

**Rationale:** Self-reported attitudes and intentions often do not predict actual behaviour. Compliance (passive following of rules) is insufficient for rapidly evolving threats; organisations need adherence—active engagement, including explaining rules and reminding others. CHARM therefore targets *actual behaviour in context*: what people do when under workload, time pressure, or usability friction. ENISA’s reviews indicate that coping capacity and self-efficacy are more reliable predictors of secure behaviour than threat appraisal, reinforcing the need to measure and influence behaviour rather than policy checkboxes alone.

---

## 3. Risk-Based Differentiation

**Definition:** Human-related risks are assessed and managed according to role, exposure, context, and impact, recognising heterogeneity in user behaviour and threat susceptibility.

**Rationale:** Different users face different risks: a finance officer or system administrator may be both higher exposure and higher impact than a generic role. One-size-fits-all awareness fails to address this. CHARM applies risk logic familiar to CISOs and regulators—likelihood, impact, amplifiers, mitigators—to human factors, producing prioritised intervention targets and enabling role-specific, context-aware interventions rather than generic training for everyone.

---

## 4. Socio-Technical Integration

**Definition:** Human behaviour is addressed in conjunction with technological usability, workflow design, and organisational pressures, reflecting the socio-technical nature of cybersecurity.

**Rationale:** Insecure behaviour is often driven by security being too complex, effortful, or misaligned with primary work goals. Studies show that workload, time pressure, and usability friction are major drivers of non-compliance; fixing policies and tools is often more effective than “fixing” the user. CHARM therefore integrates behaviour with technology and organisation: interventions may include usability-driven redesign, workflow-aligned controls, and leadership and culture, not only training.

---

## 5. Continuous Measurement and Adaptation

**Definition:** CHARM adopts an iterative approach in which interventions are continuously evaluated and refined based on behavioural evidence and incident data.

**Rationale:** The human factor in cybersecurity is never “solved”; threats and contexts evolve. One-off training or annual awareness campaigns do not produce sustained behavioural change. ENISA’s practitioner model (Awareness → Analyse → Plan → Implementation → Evaluation and iteration) emphasises that measures to improve security behaviour should be ongoing. CHARM embeds this in Layer 4 (behavioural monitoring and metrics) and Layer 5 (governance and continuous improvement), so that data from incidents and behaviour feeds back into risk assessment and control adjustment.

---

## 6. Standards and Regulatory Compatibility

**Definition:** The framework is designed to integrate seamlessly with existing cybersecurity standards and regulatory requirements, supporting governance, auditability, and accountability.

**Rationale:** CHARM is not a replacement for ISO/IEC 27001, NIST CSF, or the NIS2 Directive. It functions as a human-centric overlay that strengthens how these instruments treat human factors—often weakly operationalised—without duplicating controls. This supports organisations in regulated environments, provides traceability for audits, and advances consistent, auditable treatment of human risk across standards and regulatory regimes.

---

## Summary

| Principle | One-line summary |
| --------- | ----------------- |
| Human-as-Asset | Humans as adaptive defence layer when supported |
| Behaviour-Centred Security | Prioritise observed behaviour in context over compliance and self-report |
| Risk-Based Differentiation | Role, exposure, context, and impact drive tailored interventions |
| Socio-Technical Integration | Behaviour, technology, and organisation addressed together |
| Continuous Measurement and Adaptation | Iterative evaluation and refinement from behavioural evidence |
| Standards and Regulatory Compatibility | Overlay to ISO 27001, NIST CSF, NIS2; no duplication |

For the framework architecture and layers that implement these principles, see the [README](README.md) and [02–06 layer documents](02-Layer-1-Human-Risk-Context-Mapping.md).
