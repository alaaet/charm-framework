# Layer 4: Behaviour Monitoring and Metrics

**Layer 4** of the CHARM (Cybersecurity Human Awareness & Risk Management) framework addresses the evidence gap identified in the literature: over-reliance on self-reported attitudes and intentions, and on vanity metrics (e.g. training completion rates) that do not reflect actual behaviour. This layer emphasises the systematic collection of **behavioural evidence** and the use of **triangulated metrics** to evaluate interventions and signal emerging human-related risks.

---

## Objective

Measure **what people actually do**, not only what they report or whether they completed training. Metrics should support: (1) evaluation of intervention effectiveness, (2) leading indicators of human-related incidents, and (3) feedback into Layer 2 (risk reassessment) and Layer 5 (governance and improvement).

---

## Metric Categories

| Category | Examples |
| -------- | -------- |
| **Behavioural signals** | Phishing reporting rates (and quality of reports), MFA adoption and usage patterns, use of secure channels for sensitive actions, response to security prompts. |
| **Process deviations** | Workarounds (e.g. sharing credentials, bypassing approval flows), policy bypass patterns, shadow IT or unsanctioned tools where they increase risk. |
| **Cultural indicators** | Escalation behaviour (do people report near-misses?), peer reinforcement (do colleagues remind each other of secure practice?), response to incidents (blame vs learning). |
| **Training transfer** | Post-training behaviour change: do metrics in the categories above improve after specific interventions, and for which roles or segments? |

These categories should be used in combination. A single metric (e.g. phishing click rate) can be ambiguous without context; triangulation across technical, behavioural, and qualitative sources improves validity and reduces bias.

---

## Measurement Principles

- **Avoid over-reliance on self-report** — Surveys and self-declared intentions are useful as one input but do not substitute for observable behaviour. Where possible, use data from systems (e.g. reporting tools, authentication logs, simulated exercises) and qualitative follow-up (interviews, workshops) to interpret patterns.
- **Use triangulation** — Combine technical data (e.g. MFA adoption, reporting rates), behavioural observations (e.g. from exercises or audits), and qualitative insight (e.g. why people bypass controls) to form a more accurate picture.
- **Measure trends, not isolated events** — Single incidents or one-off metrics can be noisy. Track trends over time (e.g. reporting rate by month, by role) and use them to assess progress and trigger reassessment or refinement of controls.

ENISA’s behavioural guidance aligns with these principles: select metrics that are Specific, Measurable, Actionable, Relevant, and Time-related (SMART); use multiple measures that can be triangulated; collect pre- and post-intervention data where possible; and be aware that many common metrics (e.g. number of staff trained, intranet page visits) are “vanity metrics” that do not reliably inform how to influence behaviour.

---

## Outputs

- **Human Risk KPIs** — A set of indicators (from the categories above) that the organisation tracks regularly, with clear ownership and review cadence.
- **Leading indicators of human-related incidents** — Metrics that tend to precede or correlate with incidents (e.g. drop in reporting, increase in workarounds, decline in MFA use in a segment), so that action can be taken before serious impact.
- **Feedback for Layer 2 reassessment** — Evidence from behaviour and incidents should periodically feed back into the human risk register: update likelihood, impact, or mitigator assumptions so that risk assessment stays current.

---

## Relationship to Other Layers

- **From Layer 2 and 3:** Risk priorities and interventions define what to measure (which behaviours, which roles, which time windows).
- **To Layer 2:** Metrics and incidents drive reassessment of human risks.
- **To Layer 5:** Aggregated indicators and trends support governance reporting, accountability, and continuous improvement decisions.

For alignment with ISO 27001, NIST CSF, and NIS2 (e.g. effectiveness assessment), see [07-Alignment-with-Standards.md](07-Alignment-with-Standards.md). For maturity expectations, see [08-Maturity-Model.md](08-Maturity-Model.md).
