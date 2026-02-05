# CHARM: Cybersecurity Human Awareness & Risk Management Framework

**CHARM** is a human-centric, risk-based framework that translates findings from systematic literature on the human factor in cybersecurity into a structured, implementable model. The manuscript establishes *what* and *why*—the human factor as a socio-technical system, a taxonomy of human-related risks, and evidence that awareness-only approaches fail. CHARM answers *how*, *where*, and *with what feedback loop*: it integrates psychological science, organisational controls, and risk management into a governance-ready framework aligned with NIS2 and ENISA behavioural guidance, without duplicating them.

---

## Positioning

- **Human-as-asset**: CHARM treats people as an adaptive defence layer, not the "weakest link."
- **Continuation of SLR findings**: It embeds the human-factor taxonomy into risk management and addresses methodological weaknesses identified in the literature.
- **Overlay to existing frameworks**: CHARM is designed to integrate with ISO/IEC 27001, NIST Cybersecurity Framework (CSF) 2.0, and the NIS2 Directive—strengthening their treatment of human-related risk rather than replacing them.

---

## High-Level Architecture

CHARM is structured as **five interlocking layers** forming a closed feedback loop:

```
┌────────────────────────────────────────┐
│  Layer 5: Governance & Continuous Loop  │
├────────────────────────────────────────┤
│  Layer 4: Behaviour Monitoring & Metrics│
├────────────────────────────────────────┤
│  Layer 3: Adaptive Awareness & Controls │
├────────────────────────────────────────┤
│  Layer 2: Human Risk Assessment        │
├────────────────────────────────────────┤
│  Layer 1: Human Risk Context Mapping   │
└────────────────────────────────────────┘
```

Data and insights flow continuously: context mapping feeds risk assessment; risk assessment drives adaptive awareness and controls; behaviour monitoring provides evidence that feeds back into risk assessment and governance; governance ensures accountability and improvement across all layers.

For a full visual design specification, see [10-Visual-Model-Specification.md](10-Visual-Model-Specification.md).

---

## Design Principles

CHARM is built on six foundational principles:

1. **Human-as-Asset** — Humans as adaptive security resources, not inherent vulnerabilities.
2. **Behaviour before Compliance** — Target actual behaviour in context, not abstract policy adherence.
3. **Risk-Based Personalisation** — Different users, risk profiles, and interventions.
4. **Socio-Technical Integration** — Behaviour, usability, and organisational pressure addressed together.
5. **Continuous Measurement & Adaptation** — No one-off training; continuous sensing, feedback, and refinement.
6. **Regulatory & Standards Compatibility** — Overlay to ISO 27001, NIST CSF, and NIS2.

Details and rationale for each principle are in [01-Design-Principles.md](01-Design-Principles.md).

---

## What Makes CHARM Distinct

| Aspect           | Traditional Frameworks | CHARM                     |
| ---------------- | ---------------------- | ------------------------- |
| View of humans   | Risk source            | Adaptive control layer    |
| Awareness        | Static training        | Dynamic, risk-driven      |
| Measurement      | Compliance metrics     | Behavioural indicators     |
| Psychology       | Implicit               | Explicit & evidence-based |
| Risk integration | Peripheral             | Core                      |

---

## How to Use This Framework

1. **Understand the foundations**: Read [01-Design-Principles.md](01-Design-Principles.md) and the five layer documents (02–06) to see how human risk is mapped, assessed, treated, measured, and governed.
2. **Check alignment**: Use [07-Alignment-with-Standards.md](07-Alignment-with-Standards.md) to see how CHARM maps to ISO 27001, NIST CSF, and NIS2.
3. **Assess maturity**: Use [08-Maturity-Model.md](08-Maturity-Model.md) and [09-Assessment-Questionnaire.md](09-Assessment-Questionnaire.md) to evaluate where your organisation sits and how to improve.
4. **Communicate the model**: Use [10-Visual-Model-Specification.md](10-Visual-Model-Specification.md) to create or adapt the CHARM diagram for presentations or papers.
5. **Research and practice**: See [11-Research-and-Applications.md](11-Research-and-Applications.md) for implications and use cases.

---

## Framework Documents

| # | Document | Description |
|---|----------|-------------|
| 1 | [01-Design-Principles.md](01-Design-Principles.md) | Six foundational principles with rationale |
| 2 | [02-Layer-1-Human-Risk-Context-Mapping.md](02-Layer-1-Human-Risk-Context-Mapping.md) | Context mapping: inputs, domains, outputs |
| 3 | [03-Layer-2-Human-Risk-Assessment.md](03-Layer-2-Human-Risk-Assessment.md) | Human risk assessment: dimensions, methods, outputs |
| 4 | [04-Layer-3-Adaptive-Awareness-and-Controls.md](04-Layer-3-Adaptive-Awareness-and-Controls.md) | Adaptive awareness and human-centric controls |
| 5 | [05-Layer-4-Behaviour-Monitoring-and-Metrics.md](05-Layer-4-Behaviour-Monitoring-and-Metrics.md) | Behavioural monitoring and metrics |
| 6 | [06-Layer-5-Governance-and-Continuous-Improvement.md](06-Layer-5-Governance-and-Continuous-Improvement.md) | Governance and continuous improvement |
| 7 | [07-Alignment-with-Standards.md](07-Alignment-with-Standards.md) | Mapping to ISO 27001, NIST CSF, and NIS2 |
| 8 | [08-Maturity-Model.md](08-Maturity-Model.md) | CHARM maturity levels (1–5) |
| 9 | [09-Assessment-Questionnaire.md](09-Assessment-Questionnaire.md) | Assessment items, scoring, interpretation |
| 10 | [10-Visual-Model-Specification.md](10-Visual-Model-Specification.md) | Figure design specification for CHARM diagram |
| 11 | [11-Research-and-Applications.md](11-Research-and-Applications.md) | Contribution, implications, and use cases |
