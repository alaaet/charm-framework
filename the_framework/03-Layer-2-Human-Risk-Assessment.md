# Layer 2: Human Risk Assessment

**Layer 2** of the CHARM (Cybersecurity Human Awareness & Risk Management) framework integrates human factors into formal cybersecurity risk assessment. It bridges psychological and behavioural drivers with risk logic familiar to CISOs and regulators, producing a **human risk register** and prioritised intervention targets that feed Layer 3 (Adaptive Awareness and Controls).

---

## Objective

Quantify and prioritise **human-related cyber risks** using dimensions analogous to traditional risk management—likelihood, impact, amplifiers, and mitigators—while explicitly incorporating behavioural and psychological drivers. The output supports risk treatment decisions and aligns with enterprise risk management and regulatory expectations, including NIS2 risk management processes (Article 21).

---

## Assessment Dimensions

Human-related risks are evaluated along the following dimensions:

| Dimension | What it covers |
| --------- | ----------------- |
| **Likelihood** | Behavioural susceptibility (e.g. to social engineering), cognitive load in the role, exposure to relevant threats (e.g. phishing, credential misuse). |
| **Impact** | Access level of the role (e.g. privileged vs standard), criticality of the business function, potential cascading effects of a human-induced incident. |
| **Amplifiers** | Stress, remote work, time pressure, conflicting goals, or lack of support that increase the likelihood or severity of human-related failure. |
| **Mitigators** | Existing training quality, tooling (e.g. MFA, secure defaults), leadership support, and other controls that reduce likelihood or impact. |

Risks can be assessed per role, per scenario (e.g. “phishing under time pressure” for a given population), or per process, and then compared so that the most significant human risks are treated first.

---

## Methods

- **Scenario-based human risk modelling** — Define scenarios (e.g. phishing, insider misuse, accidental exposure) and assess likelihood and impact given the context from Layer 1 (workload, usability, culture). Example: “Phishing under time pressure for finance staff” may score higher likelihood and impact than for a low-exposure role.
- **Role-based risk scoring** — Score roles or functions on exposure, access, and behavioural/cultural factors; aggregate into a human risk profile per role or unit.
- **Integration with enterprise risk registers** — Record human-related risks in the same register as other cybersecurity risks, with clear ownership and linkage to Layer 1 context and Layer 3 treatments. This supports governance (Layer 5) and regulatory alignment (e.g. NIS2).

---

## Alignment Note

Layer 2 is directly compatible with **NIS2 risk management processes** (Article 21). Human behaviour is treated as a measurable risk factor within the organisation’s cybersecurity risk management framework, enabling traceability from risk identification through mitigation to effectiveness assessment.

---

## Outputs

- **Human Risk Register** — A structured list of human-related risks with assessed likelihood, impact, amplifiers, and mitigators, and (where applicable) linkage to roles, scenarios, or processes.
- **Prioritised intervention targets** — Risks or role/scenario combinations that warrant immediate or near-term intervention (Layer 3), based on risk level and organisational priorities.
- **Accepted vs unacceptable human risks** — Clear decisions on which risks are accepted (with justification), which are mitigated, and which are deferred, supporting governance and audit.

---

## Relationship to Other Layers

- **From Layer 1:** Context mapping defines the scope and structure for assessment (which roles, workflows, and domains to assess).
- **To Layer 3:** Prioritised risks and drivers (e.g. cognitive bias, workload stress, low self-efficacy) determine the type and targeting of interventions.
- **From Layer 4:** Behavioural metrics and incident data can trigger reassessment and refinement of likelihood, impact, or mitigator assumptions.

For alignment with ISO 27001, NIST CSF, and NIS2, see [07-Alignment-with-Standards.md](07-Alignment-with-Standards.md). For maturity expectations, see [08-Maturity-Model.md](08-Maturity-Model.md).
