<p align="center">
  <img src="images/logos/flowsignal-icon.svg" alt="FlowSignal" width="120">
</p>

<h1 align="center">FlowSignal Enterprise Architecture Library (FEAL)</h1>

<p align="center">

</p>

<p align="center">
The public architecture repository for Independent Runtime Authority,
reference architectures and enterprise implementation guidance.
</p>





The FlowSignal Enterprise Architecture Library (FEAL) is the public repository for the architectural publications defining Independent Runtime Authority.

It establishes Runtime Authority as an independent enterprise architectural capability responsible for determining whether delegated institutional authority remains legitimately exercisable immediately before consequential execution.

This repository contains the reference architectures, white papers and implementation guidance supporting that architectural discipline.
---
<p align="center">
  <a href="images/mendix/Mendix Institutional Runtime Architecture.png">
  <img src="images/mendix/Mendix Institutional Runtime Architecture.png" width="900" alt="Mendix Institutional Runtime Architecture">
</a>
</p>

<p align="center">
<i>Figure 1 – Independent Runtime Authority within the Mendix reference architecture.</i>
</p>
## Why Runtime Authority?

Enterprise systems have traditionally assumed that authority delegated during workflow approval remains valid when execution eventually occurs.

Modern AI systems, autonomous workflows and dynamic enterprise environments have changed that assumption.

Execution increasingly occurs under runtime conditions that differ from those that existed when authority was originally delegated.

Runtime Authority addresses this problem by introducing an independent determination immediately before consequential execution.

Rather than asking:

> **"Was this workflow approved?"**

Runtime Authority asks:

> **"Is delegated authority still legitimately exercisable now?"**

---

# Publications

| Document | Description | Status |
|-----------|-------------|:------:|
| **[FEAL-001](docs/FEAL-001-Institutional-Runtime-Architecture.pdf)** | Institutional Runtime Architecture | ✅ Released |
| **[FP-001](docs/FP-001-Runtime-Authority-Control.pdf)** | Runtime Authority Control | ✅ Released |
| **[FS-ARCH-003](docs/FS-ARCH-003-Mendix-Reference-Architecture.pdf)** | Mendix Reference Architecture | ✅ Released |

*Additional publications will be released as the architecture library expands.*
---

# Reference Implementation (FlowSignal MVP)

The FlowSignal MVP demonstrates the practical implementation of Independent Runtime Authority within a working enterprise application.

Current capabilities include:

- Independent Runtime Authority
- Deterministic **ALLOW / ESCALATE / REFUSE** decisions
- Execution Bind Point
- Authority Receipts
- Evidence Continuum
- Defensible Execution

The screenshots included within this repository have been captured directly from the running FlowSignal MVP and represent operational output rather than conceptual illustrations.
<p align="center">
  <img src="Example/Screenshot MVP FlowSignal 1.png" width="950" alt="FlowSignal Runtime Authority Dashboard">
</p>

<p align="center">
<i>FlowSignal MVP demonstrating a deterministic Runtime Authority determination at the Execution Bind Point, resulting in a signed Authority Receipt.</i>
</p>

---

# Repository Contents 

```
docs/
    FEAL publications and reference architectures

images/
    Architecture diagrams and supporting figures

images/mendix/
    Figures supporting FS-ARCH-003

Example/
    MVP screenshots and implementation examples
```

---

# Relationship Between the Publications

The publications are intended to be read together.

| Publication | Purpose |
|-------------|---------|
| **FP-001** | Introduces Runtime Authority Control as an independent enterprise capability. |
| **FEAL-001** | Defines the Institutional Runtime Architecture. |
| **FS-ARCH-003** | Demonstrates implementation of FEAL-001 within the Mendix platform. |

Future reference architectures will demonstrate implementation patterns for additional enterprise platforms.

---

# Architectural Principles

The FlowSignal architecture is founded upon the following principles:

- Independent
- Deterministic
- Platform Agnostic
- Evidence-Based
- Explainable
- Defensible

---

# Roadmap

The architecture library will continue to expand with additional publications, including:

- SAP Reference Architecture
- ServiceNow Reference Architecture
- Microsoft Power Platform Reference Architecture
- Runtime Authority Technical Specification
- Conformance Test Suite
- Additional implementation guidance

---

# Feedback

The FlowSignal Enterprise Architecture Library is published to encourage technical discussion and peer review.

Feedback from enterprise architects, governance specialists, platform providers and AI practitioners is welcomed.

---

# About FlowSignal

FlowSignal develops Independent Runtime Authority as an enterprise architectural capability for autonomous and AI-enabled systems.

The FlowSignal platform is the first public reference implementation of the FlowSignal Enterprise Architecture Library (FEAL).

https://flowsignal.ai

---

## Vision

Independent Runtime Authority proposes that Runtime Authority should become the next foundational responsibility within Enterprise Architecture, providing institutions with a deterministic mechanism to determine whether delegated authority remains legitimately exercisable immediately before consequential execution.

FlowSignal is the first public reference implementation of that architectural discipline.
# License

This repository is released under the Apache 2.0 License.

---

**Version:** 1.0  
**Initial Public Release:** July 2026

© 2026 FlowSignal. All rights reserved.
