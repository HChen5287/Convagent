# Conv-Agent Reproduction Skill Specification

> **An ontology-centric multi-agent engineering specification for reproducing the Conv-Agent framework through Skill Engineering.**

---

## Overview

This repository accompanies the research paper:

> **Agentic AI Neural-Based Ontology Building and High-Quality Data Re-form Approach for Predictive Management of Wellbore and Transmission Pipelines**

Rather than releasing the complete production source code, this repository provides a comprehensive **Skill-based engineering specification** that enables researchers and engineers to independently reproduce the Conv-Agent framework.

Conv-Agent is an ontology-driven, multi-agent architecture inspired by the computational principles of convolutional neural networks (CNNs). By replacing numerical feature extraction with distributed semantic reasoning, Conv-Agent performs ontology construction, ontology optimisation, High-Quality Dataset (HQD) generation, and autonomous workflow planning for complex industrial decision-making tasks.

---

## Why This Repository?

The production implementation of Conv-Agent contains proprietary optimisation algorithms, enterprise deployment components, confidential engineering assets, and industrial software modules that cannot be publicly released due to intellectual property protection and commercial confidentiality requirements.

To promote academic reproducibility while protecting production assets, this repository publishes the complete **Skill Specification** used to reproduce the Conv-Agent framework.

Instead of providing implementation-specific source code, this repository describes the complete engineering methodology through modular Skills that can be implemented using different programming languages, AI models, deployment environments, and software stacks.

---

## Repository Structure

```text
Conv-Agent-Reproduction/
│
├── README.md
├── LICENSE
├── CITATION.cff
├── docs/
│   ├── Preface.md
│   ├── Architecture.md
│   ├── Runtime.md
│   └── Figures/
│
├── examples/
│   ├── Sample_Datasets/
│   ├── Ontology_Examples/
│   └── Skill_Examples/
│
└── wiki/
    ├── 01_System_Initialisation_Skill.md
    ├── 02_Runtime_Environment_Skill.md
    ├── 03_Foundation_Model_Skill.md
    ├── 04_Skill_Lifecycle_Management.md
    ├── 05_Multi-Agent_Collaboration.md
    ├── 06_Ontology_Representation.md
    ├── 07_Ontology_Convolution.md
    ├── 08_Semantic_Pooling.md
    ├── 09_Ontology_Fusion.md
    ├── 10_HQD_Construction.md
    ├── 11_System_Evaluation.md
    ├── 12_Experiment_Reproduction.md
    └── 13_Continuous_Evolution.md
```

---

# Wiki Contents

The **GitHub Wiki** is the primary documentation for reproducing Conv-Agent.

It contains the complete engineering Skill specification required to reconstruct the system described in the accompanying paper.

Each chapter corresponds to one executable engineering Skill and collectively forms the complete Conv-Agent reproduction workflow.

The Wiki covers:

- system initialisation;
- runtime environment deployment;
- foundation model orchestration;
- Skill lifecycle management;
- multi-agent collaboration;
- ontology representation;
- ontology convolution;
- semantic pooling;
- ontology fusion;
- HQD construction;
- system evaluation;
- experiment reproduction;
- continuous Skill evolution.

No production source code is included.

Instead, each chapter provides sufficient engineering guidance for independent implementation.

---

# Skill Engineering

Conv-Agent adopts a unified Skill representation:

```text
Skill = <M, R, C>
```

where:

| Component | Description |
|-----------|-------------|
| **M (Manual)** | Execution procedures, engineering logic, workflow definitions, and expected outputs. |
| **R (Resources)** | Models, datasets, APIs, templates, databases, and supporting resources required by the Skill. |
| **C (Conditions)** | Activation conditions, execution constraints, convergence criteria, and dependency rules. |

This representation enables both human developers and AI agents to interpret and execute the same engineering workflow.

---

# What Is Included

This repository includes:

- Conv-Agent reproduction methodology;
- Skill Engineering specification;
- ontology construction workflow;
- HQD construction methodology;
- runtime architecture description;
- deployment guidance;
- engineering best practices;
- sample datasets;
- ontology examples;
- evaluation methodology;
- experiment reproduction guidance.

---

# What Is Not Included

To comply with intellectual property and industrial confidentiality requirements, this repository does **not** include:

- production source code;
- enterprise deployment scripts;
- proprietary optimisation algorithms;
- confidential industrial datasets;
- internal software frameworks;
- commercial APIs;
- private model weights;
- production Skill repositories.

Readers are encouraged to implement their own Conv-Agent systems based on the publicly available specification.

---

# Reproducing Conv-Agent

The recommended reading order is:

1. Read the accompanying research paper.
2. Review the architectural overview in the documentation.
3. Follow the deployment guidance.
4. Read the Wiki sequentially from Chapter 1 to Chapter 13.
5. Implement each Skill independently.
6. Integrate all Skills into a complete Conv-Agent runtime.
7. Validate the system using the provided evaluation methodology.

---

# Intended Audience

This repository is intended for:

- AI researchers;
- software engineers;
- ontology engineers;
- data engineers;
- industrial AI practitioners;
- researchers working on AI for Science;
- developers building autonomous agent systems.

---

# Citation

If you use this repository in academic research, please cite the accompanying paper.

A `CITATION.cff` file is provided for GitHub citation support.

---

# Licence

The documentation in this repository is released under the licence specified in the `LICENSE` file.

The Conv-Agent methodology may be reproduced for academic research and engineering implementation in accordance with the applicable licence terms.

---

# Disclaimer

This repository is an **engineering reproduction specification**, not an official software release.

The documentation aims to facilitate transparent, reproducible, and extensible research on ontology-centric autonomous agent systems while protecting proprietary implementation details.

Independent implementations derived from this specification remain the responsibility of their respective developers.

---

# Maintainers

Conv-Agent Research Project

For technical discussions, feature suggestions, or academic collaboration, please use the GitHub **Issues** and **Discussions** sections.

---

> **"The paper explains why Conv-Agent works.  
> This repository explains how to reproduce it."**
