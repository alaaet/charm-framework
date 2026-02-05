# Layer 1: Human Risk Context Mapping

**Layer 1** of the CHARM (Cybersecurity Human Awareness & Risk Management) framework establishes a contextual understanding of how human factors manifest within a specific organisational environment. It operationalises the human-factor taxonomy from the systematic literature into a **living organisational map** that serves as the foundation for risk assessment (Layer 2) and intervention design (Layer 3).

---

## Objective

Create a **contextualised human risk landscape** for the organisation: who is exposed, in what roles and workflows, under what pressures, and with what technological and cultural influences. This layer does not yet quantify risk; it maps the terrain so that Layer 2 can assess and prioritise effectively.

---

## Inputs

- **Organisational structure and roles** — How the organisation is organised; which roles exist; which functions handle sensitive data or critical processes.
- **Workflows and task pressure points** — Where time pressure, productivity demands, or conflicting goals create security–productivity trade-offs.
- **Technology usability friction** — Where security controls (e.g. authentication, encryption, approval workflows) are cumbersome, unclear, or misaligned with how people actually work.
- **Security culture indicators** — Leadership attitudes to security; whether security is seen as enabling or obstructing; how incidents and near-misses are treated (blame vs learning).

---

## Human Risk Domains

Drawing from the manuscript taxonomy and CHARM’s socio-technical view, human risk is structured into five domains. Each domain should be considered across roles, processes, and technologies when building the context map.

| Domain | Description |
| ------ | ----------- |
| **Cognitive** | Biases, heuristics, mental models; how people interpret warnings, assess risk, or simplify decisions under load. |
| **Behavioural** | Workarounds, habits, shortcuts; routine deviations from policy when it conflicts with perceived productivity or ease. |
| **Social** | Authority, trust, social proof; susceptibility to social engineering; influence of peers and leadership on security behaviour. |
| **Organisational** | Culture, leadership, workload, incentives; whether security is prioritised or tacitly deprioritised in favour of delivery. |
| **Socio-technical** | HCI, usability, alert fatigue; fit between security mechanisms and the way work is done; design-induced errors or bypass. |

These domains are interdependent: for example, organisational pressure (high workload) can amplify cognitive load and increase reliance on shortcuts (behavioural) and reduce attention to security cues (socio-technical).

---

## Key Activities

- **Identify high-exposure roles and functions** — e.g. finance, administrators, executives, roles with privileged access or handling of sensitive data.
- **Map workflow-induced pressures and security–productivity trade-offs** — where do people feel they must choose between “doing the job” and “following security”?
- **Document usability frictions in security controls** — which controls are avoided, circumvented, or poorly understood?
- **Assess cultural and leadership influences on security behaviour** — is non-compliance addressed constructively; is security visibly supported by leadership?

A multi-method approach is recommended: combine quantitative data (e.g. incident patterns, access logs) with qualitative insight (interviews, workshops) and consider multiple levels of the organisation (individual, team, leadership). ENISA’s behavioural guidance emphasises that awareness and analysis should look at the organisation, work processes, and local factors together; many “human” problems have causes outside the individual, including unworkable policies or tools.

---

## Outputs

- **Human Risk Map by role/function** — A structured view of where human factors are most relevant: which roles, which workflows, which technologies, and which domains (cognitive, behavioural, social, organisational, socio-technical) are salient.
- **Identification of high-exposure human nodes** — Roles or functions that are both exposed to human-related risk and critical to business or security (e.g. finance, admins, executives). These become priority candidates for Layer 2 assessment and Layer 3 interventions.

---

## Relationship to Other Layers

- **To Layer 2:** The context map provides the scope and structure for human risk assessment: which roles and scenarios to assess, and which dimensions (likelihood, impact, amplifiers, mitigators) to apply.
- **From Layer 4 and 5:** Incident data and behavioural metrics can update the context map over time (e.g. new pressure points, new workarounds), keeping it a living artefact.

For alignment of this layer with ISO 27001, NIST CSF, and NIS2, see [07-Alignment-with-Standards.md](07-Alignment-with-Standards.md). For maturity expectations, see [08-Maturity-Model.md](08-Maturity-Model.md).
