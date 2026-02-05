# CHARM Visual Model Specification

This document provides a design specification for the CHARM (Cybersecurity Human Awareness & Risk Management) framework figure. It is intended for implementers—graphic designers, or those recreating the figure in tools such as Illustrator, PowerPoint, Figma, Visio, or LaTeX (TikZ)—and for reviewers who need to understand the visual model without ambiguity. A formal figure caption and in-text reference example are included for publication use.

---

## 1. Overall Visual Concept

**Figure type:** Layered circular system with governance envelope and feedback loop.

**Rationale:**

- Circularity emphasises **continuous risk management**, not linear training.
- Layers reflect **increasing operational maturity** (from context at the core to governance at the outer ring).
- Outer governance ring signals **executive accountability and regulation**.
- Feedback arrows reinforce **learning and adaptation**.

This visually differentiates CHARM from linear awareness models, control checklists, and maturity ladders.

---

## 2. High-Level Structure

The figure consists of **three structural elements**:

1. **Five concentric layers (core → outer)** — Layer 1 at the centre, Layer 5 at the outer ring.
2. **A surrounding governance boundary** — A thin frame around the entire model.
3. **Bidirectional feedback arrows** — Inner circular flow and vertical flow between adjacent layers.

**ASCII sketch:**

```
[ Governance & Regulatory Oversight ]
┌───────────────────────────────────┐
│   Layer 5: Governance & Improvement │
│ ┌───────────────────────────────┐  │
│ │ Layer 4: Behaviour Monitoring │  │
│ │ ┌───────────────────────────┐ │  │
│ │ │ Layer 3: Adaptive Controls│ │  │
│ │ │ ┌───────────────────────┐ │ │  │
│ │ │ │ Layer 2: Risk Assess. │ │ │  │
│ │ │ │ ┌───────────────────┐ │ │ │  │
│ │ │ │ │ Layer 1: Context  │ │ │ │  │
│ │ │ │ └───────────────────┘ │ │ │  │
│ │ │ └───────────────────────┘ │ │  │
│ │ └───────────────────────────┘ │  │
│ └───────────────────────────────┘  │
└───────────────────────────────────┘
```

---

## 3. Layer-by-Layer Visual Design

### Core (Centre) — Layer 1: Human Risk Context Mapping

**Label (inside circle):** *Human Risk Context*

**Sub-labels (small text or icons):** Cognitive • Behavioural • Social • Organisational • Socio-technical

**Design cues:** Neutral colour (light grey or soft blue). Represents baseline human reality; no “controls” yet—only understanding.

---

### Second Ring — Layer 2: Human Risk Assessment

**Label:** *Human Risk Assessment*

**Icons / keywords (optional):** Likelihood • Impact • Exposure • Amplifiers

**Design cues:** Slightly darker tone. Introduces risk logic; connects human factors to formal cybersecurity language.

---

### Third Ring — Layer 3: Adaptive Awareness & Human-Centric Controls

**Label:** *Adaptive Awareness & Controls*

**Sub-elements (radial segments or callouts):** Role-based awareness • Usability-aligned controls • Bias-aware interventions • Just-in-time support

**Design cues:** Primary accent colour. This is the operational heart of CHARM; distinct from “training” terminology.

---

### Fourth Ring — Layer 4: Behaviour Monitoring & Metrics

**Label:** *Behaviour Monitoring & Metrics*

**Keywords/icons:** Observed behaviour • Leading indicators • Triangulation • Feedback signals

**Design cues:** Data-oriented colour (e.g. teal or purple). Suggests sensing, telemetry, evidence; avoid “surveillance” connotation.

---

### Fifth Ring — Layer 5: Governance & Continuous Improvement

**Label:** *Governance & Continuous Improvement*

**Keywords:** Leadership oversight • Risk ownership • Policy adaptation • Learning loops

**Design cues:** Strong, stable colour (e.g. dark blue or charcoal). Represents authority and accountability; links CHARM to boards and regulators.

---

## 4. Governance & Regulatory Boundary (Outer Frame)

Surround the entire model with a **thin enclosing rectangle or circle** labelled:

**Cybersecurity Governance & Regulatory Context**  
*(ISO/IEC 27001 • NIST CSF • NIS2)*

**Purpose:** Signals compliance compatibility; makes clear CHARM is embedded in existing frameworks, not parallel. Reviewer-friendly positioning.

---

## 5. Feedback & Flow Arrows

Include **two arrow systems**:

### A. Inner Circular Arrow (Clockwise)

- Runs across Layers 2 → 5 → back to Layer 1.
- Label: *Continuous Human Risk Lifecycle*

### B. Bidirectional Vertical Arrows

- Between adjacent layers.
- Indicates: *Assessment ↔ Intervention ↔ Measurement*

This reinforces that metrics influence controls, controls reshape context, and context updates risk models.

---

## 6. Optional Comparative Annotation (Reviewer-Friendly)

In the bottom corner or caption note:

*CHARM embeds human behaviour across the cybersecurity risk lifecycle, extending beyond awareness-centric models.*

This pre-empts reviewer concerns about novelty.

---

## 7. Formal Figure Caption (Journal-Ready)

**Figure X. The CHARM Framework: Cybersecurity Human Awareness & Risk Management.**

The figure illustrates CHARM as a five-layer, iterative framework integrating human factors into the cybersecurity risk lifecycle. The model progresses from contextual mapping of human-related risks through formal risk assessment, adaptive awareness and control implementation, and behaviour-based monitoring, culminating in governance and continuous improvement. A surrounding governance boundary highlights alignment with ISO/IEC 27001, NIST CSF, and NIS2 requirements. Bidirectional feedback loops emphasise continuous learning and adaptation.

---

## 8. In-Text Reference Example

*Figure X presents the CHARM framework as an iterative, risk-based model in which human behaviour is treated as a dynamic component of cybersecurity governance rather than a static compliance issue.*

---

For the conceptual description of each layer, see [02–06](02-Layer-1-Human-Risk-Context-Mapping.md). For alignment with standards, see [07-Alignment-with-Standards.md](07-Alignment-with-Standards.md).
