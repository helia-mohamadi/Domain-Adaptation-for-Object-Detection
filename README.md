# 🌟 Domain Adaptation Methods: A Hierarchical Dual-Axis Taxonomy
*A curated, reproducible, and fully categorized collection of Domain Adaptation literature, organized under a novel two-axis classification scheme.*

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)
[![Papers](https://img.shields.io/badge/Papers-750+-blue.svg)](#)
[![Taxonomy](https://img.shields.io/badge/Taxonomy-Dual--Axis-purple.svg)](#)

---

## 🧭 The Proposed Taxonomy (Axis-1: Methodological Families)

Unlike prior repositories that organize papers by *application* or *supervision regime*, this repository organizes **every method** under six **methodological families**, each refined into hierarchical **sub-branches** (our novel refinement):

```mermaid
graph TD
    A[Domain Adaptation Methods] --> B[Discrepancy-based]
    A --> C[Adversarial-based]
    A --> D[Multi-Domain based]
    A --> E[Ensemble-Based]
    A --> F[Teacher-Student based]
    A --> G[VLM / Foundation based]
    B --> B1[Moment & Distance Matching]
    B --> B2[Optimal Transport]
    B --> B3[Statistics & Structure Matching]
    C --> C1[Adversarial Feature Alignment]
    C --> C2[Adversarial Pixel/Style Translation]
    C --> C3[Adversarial Output-Space Alignment]
    D --> D1[Multi-Source / Multi-Target]
    D --> D2[Continual / Incremental / Federated]
    D --> D3[Compound & Heterogeneous Shifts]
    E --> E1[Co-Training & Committee Consistency]
    E --> E2[Mixture-of-Experts & Aggregation]
    F --> F1[Mean-Teacher & Temporal Ensembling]
    F --> F2[Self-Training & Pseudo-Labeling]
    F --> F3[Knowledge Distillation]
    G --> G1[Prompt / Adapter Tuning]
    G --> G2[Vision-Language Distillation]
    G --> G3[Zero-Shot VLM Adaptation]
