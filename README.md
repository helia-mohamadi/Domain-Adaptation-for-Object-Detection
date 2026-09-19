# 📚 Awesome Domain Adaptation for Object Detection & Beyond

[![MIT License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

Welcome to this curated repository of research papers focused on **Domain Adaptation (DA)** in computer vision. This collection is meticulously categorized based on the primary methodological approach of each paper, specifically highlighting feature-based adaptation techniques, adversarial training, discrepancy minimization, multi-domain approaches, and modern vision-language integrations.

This repository merges foundational references, recent breakthroughs, and comprehensive lists (including `awesome-domain-adaptation`) into an easy-to-navigate format for researchers and practitioners.

---

## 🗂️ Categorized Paper List (By Primary Methodology)

This table categorizes each domain adaptation paper into its core methodology, allowing for a quick overview of the architectural approaches used across the literature. 

| Category | Article Title | Year | Links |
| :--- | :--- | :--- | :--- |
| **Discrepancy-Based** | DATR: Unsupervised Domain Adaptive Detection Transformer With Dataset-Level Adaptation | 2025 | [[Code]](https://github.com/h751410234/DATR) |
| **Discrepancy-Based** | Differential Alignment for Domain Adaptive Object Detection | 2025 | [[Code]](https://github.com/EstrellaXyu/Differential-Alignment-for-DAOD) |
| **Discrepancy-Based** | Unsupervised Domain-Adaptive Object Detection via Localization Regression Alignment | 2024 | |
| **Discrepancy-Based** | JFDI: Joint Feature Differentiation and Interaction for domain adaptive object detection | 2024 | |
| **Discrepancy-Based** | Unsupervised Concept Drift Detection from Deep Learning Representations in Real-time | 2024 | [[Code]](https://github.com/grecosalvatore/drift-lens) |
| **Discrepancy-Based** | Robust Domain Adaptive Object Detection With Unified Multi-Granularity Alignment | 2024 | |
| **Discrepancy-Based** | Diverse Feature-Level Guidance Adjustments for Unsupervised Domain Adaptative Object Detection | 2024 | |
| **Discrepancy-Based** | Concept drift adaptation with continuous kernel learning | 2024 | |
| **Discrepancy-Based** | Towards Discriminability with Distribution Discrepancy Constrains for Multisource DA | 2024 | |
| **Discrepancy-Based** | A benchmark and survey of fully unsupervised concept drift detectors on real-world data streams | 2024 | |
| **Discrepancy-Based** | SPA: A Graph Spectral Alignment Perspective for Domain Adaptation | 2023 | [[Code]](https://github.com/CrownX/SPA) |
| **Discrepancy-Based** | Instance Relation Graph Guided Source-Free Domain Adaptive Object Detection | 2023 | |
| **Discrepancy-Based** | Decompose to Adapt: Cross-Domain Object Detection Via Feature Disentanglement | 2023 | |
| **Discrepancy-Based** | C2FDA: Coarse-to-Fine Domain Adaptation for Traffic Object Detection | 2022 | |
| **Discrepancy-Based** | Exploring Sequence Feature Alignment for Domain Adaptive Detection Transformers | 2022 | |
| **Discrepancy-Based** | RFA-Net: Reconstructed Feature Alignment Network for Domain Adaptation Object Detection | 2022 | |
| **Discrepancy-Based** | Discrepancy-Based Active Learning for Domain Adaptation | 2022 | [[Code]](https://github.com/michelin/dbal) |
| **Discrepancy-Based** | Cross-Domain Gradient Discrepancy Minimization for Unsupervised Domain Adaptation | 2021 | [[Code]](https://github.com/lijin118/CGDM) |
| **Discrepancy-Based** | Domain Conditioned Adaptation Network | 2020 | [[Code]](https://github.com/BIT-DA/DCAN) |
| **Discrepancy-Based** | HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation | 2020 | [[Code]](https://github.com/chenchao666/HoMM-Master) |
| **Discrepancy-Based** | Exploring Categorical Regularization for Domain Adaptive Object Detection | 2020 | |
| **Discrepancy-Based** | Sliced Wasserstein Discrepancy for Unsupervised Domain Adaptation | 2019 | |
| **Discrepancy-Based** | Adapting Object Detectors via Selective Cross-Domain Alignment | 2019 | |
| **Discrepancy-Based** | Transferable Representation Learning with Deep Adaptation Networks | 2018 | |
| **Discrepancy-Based** | Deep Transfer Learning with Joint Adaptation Networks | 2017 | [[Code]](https://github.com/thuml/Xlearn) |
| **Discrepancy-Based** | Central Moment Discrepancy for Unsupervised Domain Adaptation | 2017 | [[Code]](https://github.com/wzell/cmd) |
| **Discrepancy-Based** | Deep CORAL: Correlation Alignment for Deep Domain Adaptation | 2016 | |
| **Discrepancy-Based** | Unsupervised Domain Adaptation with Residual Transfer Networks | 2016 | [[Code]](https://github.com/thuml/Xlearn) |
| **Discrepancy-Based** | Learning Transferable Features with Deep Adaptation Networks (DAN) | 2015 | [[Code]](https://github.com/thuml/DAN) |
| **Discrepancy-Based** | Deep Domain Confusion: Maximizing for Domain Invariance | 2014 | |
| **Discrepancy-Based** | What you saw is not what you get: Domain adaptation using asymmetric kernel transforms | 2011 | |
| **Adversarial-Based** | Domain Adaptive Object Detection via Dual-Stream Bilevel-Cycle Optimization | 2026 | |
| **Adversarial-Based** | RT-DATR: Real-time Unsupervised Domain Adaptive Detection Transformer with Adversarial Learning | 2025 | |
| **Adversarial-Based** | CMDA: Cross-Modal and Domain Adversarial Adaptation for LiDAR-Based 3D Object Detection | 2024 | |
| **Adversarial-Based** | Disentangled Discriminator for Unsupervised Domain Adaptation on Object Detection | 2023 | |
| **Adversarial-Based** | Reusing the Task-specific Classifier as a Discriminator: Discriminator-free Adversarial DA | 2022 | [[Code]](https://github.com/xiaoachen98/DALN) |
| **Adversarial-Based** | A Closer Look at Smoothness in Domain Adversarial Training | 2022 | [[Code]](https://github.com/val-iisc/SDAT) |
| **Adversarial-Based** | ToAlign: Task-oriented Alignment for Unsupervised Domain Adaptation | 2021 | [[Code]](https://github.com/microsoft/UDA) |
| **Adversarial-Based** | Adversarial Unsupervised Domain Adaptation With Conditional and Label Shift | 2021 | |
| **Adversarial-Based** | MetaAlign: Coordinating Domain Alignment and Classification for Unsupervised DA | 2021 | [[Code]](https://github.com/microsoft/UDA) |
| **Adversarial-Based** | Classes Matter: A Fine-grained Adversarial Approach to Cross-domain Semantic Segmentation | 2020 | [[Code]](https://github.com/JDAI-CV/FADA) |
| **Adversarial-Based** | Gradually Vanishing Bridge for Adversarial Domain Adaptation | 2020 | [[Code]](https://github.com/cuishuhao/GVB) |
| **Adversarial-Based** | Implicit Class-Conditioned Domain Alignment for Unsupervised Domain Adaptation | 2020 | [[Code]](https://github.com/xiangdal/implicit_alignment) |
| **Adversarial-Based** | Discriminative Adversarial Domain Adaptation | 2020 | [[Code]](https://github.com/huitangtang/DADA-AAAI2020) |
| **Adversarial-Based** | Progressive Domain Adaptation for Object Detection | 2020 | |
| **Adversarial-Based** | A Robust Learning Approach to Domain Adaptive Object Detection | 2019 | |
| **Adversarial-Based** | Semi-Supervised Domain Adaptation via Minimax Entropy | 2019 | |
| **Adversarial-Based** | Cycle-consistent Conditional Adversarial Transfer Networks | 2019 | [[Code]](https://github.com/lijin118/3CATN) |
| **Adversarial-Based** | Domain-Symmetric Networks for Adversarial Domain Adaptation | 2019 | [[Code]](https://github.com/YBZh/SymNets) |
| **Adversarial-Based** | Conditional Adversarial Domain Adaptation (CDAN) | 2018 | [[Code]](https://github.com/thuml/CDAN) |
| **Adversarial-Based** | CyCADA: Cycle-Consistent Adversarial Domain Adaptation | 2018 | [[Code]](https://github.com/jhoffman/cycada_release) |
| **Adversarial-Based** | Maximum Classifier Discrepancy for Unsupervised Domain Adaptation (MCD) | 2018 | [[Code]](https://github.com/mil-tokyo/MCD_DA) |
| **Adversarial-Based** | Domain Adaptive Faster R-CNN for Object Detection in the Wild | 2018 | |
| **Adversarial-Based** | Cross-Domain Weakly-Supervised Object Detection Through Progressive Domain Adaptation | 2018 | |
| **Adversarial-Based** | Generate To Adapt: Aligning Domains using Generative Adversarial Networks | 2018 | [[Code]](https://github.com/yogeshbalaji/Generate_To_Adapt) |
| **Adversarial-Based** | Adversarial Discriminative Domain Adaptation (ADDA) | 2017 | [[Code]](https://github.com/erictzeng/adda) |
| **Adversarial-Based** | Domain-Adversarial Training of Neural Networks (DANN) | 2016 | [[Code]](https://github.com/ddtm/caffe/tree/grl) |
| **Multi-Domain Based**| Attention-Based Class-Conditioned Alignment for Multi-Source Domain Adaptation | 2025 | |
| **Multi-Domain Based**| Multi-Source Domain Adaptation for Object Detection with Prototype-based Mean Teacher | 2024 | |
| **Multi-Domain Based**| Collaborative Learning for Multi-Source Domain Adaptative Object Detection | 2024 | |
| **Multi-Domain Based**| DANE: A Dual-Level Alignment Network With Ensemble Learning for Multisource Domain Adaptation | 2024 | |
| **Multi-Domain Based**| CoNMix for Source-free Single and Multi-target Domain Adaptation | 2023 | [[Code]](https://github.com/vcl-iisc/CoNMix) |
| **Multi-Domain Based**| Incremental multi-target domain adaptation for object detection with efficient domain transfer | 2022 | |
| **Multi-Domain Based**| Multi-Target Domain Adaptation with Collaborative Consistency Learning | 2021 | |
| **Multi-Domain Based**| mDALU: Multi-Source Domain Adaptation and Label Unification With Partial Datasets | 2021 | |
| **Multi-Domain Based**| Active Universal Domain Adaptation | 2021 | |
| **Multi-Domain Based**| Open Compound Domain Adaptation | 2020 | [[Code]](https://github.com/zhmiao/OpenCompoundDomainAdaptation-OCDA) |
| **Multi-Domain Based**| Domain Aggregation Networks for Multi-Source Domain Adaptation | 2020 | |
| **Multi-Domain Based**| Learning to Combine: Knowledge Aggregation for Multi-Source Domain Adaptation | 2020 | [[Code]](https://github.com/ChrisAllenMing/LtC-MSDA) |
| **Multi-Domain Based**| Moment Matching for Multi-Source Domain Adaptation | 2019 | [[Code]](http://ai.bu.edu/M3SDA/) |
| **Multi-Domain Based**| Adversarial Multiple Source Domain Adaptation (MDAN) | 2018 | [[Code]](https://github.com/KeiraZhao/MDAN) |
| **Ensemble-Based**    | Scale-Consistent and Temporally Ensembled Unsupervised Domain Adaptation for Object Detection | 2025 | |
| **Ensemble-Based**    | Ensemble of Experts for Multi-Source Unsupervised Domain Adaptation in 3D Object Detection | 2025 | |
| **Ensemble-Based**    | Domain Adaptive Ensemble Learning | 2020 | |
| **Teacher-Student**   | Expert-Teacher-Student Collaborative Learning for Domain Adaptive Object Detection | 2026 | |
| **Teacher-Student**   | Prototype-oriented contrastive mean-teacher for unsupervised domain adaptive object detection | 2026 | |
| **Teacher-Student**   | Domain-Invariant Progressive Knowledge Distillation for UAV-Based Object Detection | 2025 | |
| **Teacher-Student**   | Mean teacher DETR with masked feature alignment: a robust domain adaptive detection framework | 2024 | |
| **Teacher-Student**   | Unsupervised Video Domain Adaptation with Masked Pre-Training and Collaborative Self-Training | 2024 | [[Code]](https://github.com/reddyav1/unite) |
| **Teacher-Student**   | Contrastive Mean Teacher for Domain Adaptive Object Detectors | 2023 | |
| **Teacher-Student**   | MIC: Masked Image Consistency for Context-Enhanced Domain Adaptation | 2023 | [[Code]](https://github.com/lhoyer/MIC) |
| **Teacher-Student**   | Masked Retraining Teacher-Student Framework for Domain Adaptive Object Detection | 2023 | |
| **Teacher-Student**   | DaFKD: Domain-aware Federated Knowledge Distillation | 2023 | |
| **Teacher-Student**   | Cycle Self-Training for Domain Adaptation | 2021 | |
| **Teacher-Student**   | ST3D: Self-training for Unsupervised Domain Adaptation on 3D Object Detection | 2021 | |
| **Teacher-Student**   | Domain Adaptation With Auxiliary Target Domain-Oriented Classifier | 2021 | |
| **Teacher-Student**   | Instance Adaptive Self-Training for Unsupervised Domain Adaptation | 2020 | [[Code]](https://github.com/bupt-ai-cz/IAST-ECCV2020) |
| **Teacher-Student**   | Label Propagation with Augmented Anchors: A Simple SSL baseline for UDA | 2020 | [[Code]](https://github.com/YBZh/Label-Propagation-with-Augmented-Anchors) |
| **Teacher-Student**   | Do We Really Need to Access the Source Data? Source Hypothesis Transfer (SHOT) | 2020 | [[Code]](https://github.com/tim-learn/SHOT) |
| **Teacher-Student**   | Domain Adaptive Semantic Segmentation Using Weak Labels | 2020 | |
| **Teacher-Student**   | Semi-Supervised Domain Adaptation via Minimax Entropy | 2019 | [[Code]](https://github.com/VisionLearningGroup/SSDA_MME) |
| **Teacher-Student**   | Automatic Adaptation of Object Detectors to New Domains Using Self-Training | 2019 | |
| **VLM Based**         | Domain adaptive object detection via CLIP-space guidance and LoRA fine-tuning | 2026 | |
| **VLM Based**         | Controllable Prompt Tuning For Balancing Group Distributional Robustness | 2024 | [[Code]](https://github.com/VietHoang1512/CPT) |
| **VLM Based**         | Enhancing Domain Adaptation through Prompt Gradient Alignment | 2024 | [[Code]](https://github.com/VietHoang1512/PGA) |
| **VLM Based**         | VLDadaptor: Domain Adaptive Object Detection With Vision-Language Model Distillation | 2024 | |
| **VLM Based**         | Empowering Unsupervised Domain Adaptation with Large-scale Pre-trained Vision-Language Models | 2024 | |
| **VLM Based**         | Domain Adaptation for Large-Vocabulary Object Detectors | 2024 | |
| **VLM Based**         | POUF: Prompt-oriented unsupervised fine-tuning for large pre-trained models | 2023 | [[Code]](https://github.com/korawat-tanwisuth/POUF) |
| **VLM Based**         | Learning Domain-Aware Detection Head with Prompt Tuning | 2023 | |
| **VLM Based**         | Semi-Supervised Domain Generalization for Object Detection via Language-Guided Feature Alignment | 2023 | |
| **VLM Based**         | Grounded Language-Image Pre-training (GLIP) | 2022 | |

---

## 📅 Chronological Paper List (Sorted by Year)

For researchers looking to trace the evolution of domain adaptation, this table presents the curated list of papers sorted chronologically from the most recent publications back to the foundational architectures.

| Year | Article Title | Published In |
| :--- | :--- | :--- |
| **2026** | Domain adaptive object detection via CLIP-space guidance and LoRA fine-tuning | Expert Systems with Applications |
| **2026** | Domain Adaptive Object Detection via Dual-Stream Bilevel-Cycle Optimization | arXiv |
| **2026** | Expert-Teacher-Student Collaborative Learning for Domain Adaptive Object Detection | CVPR |
| **2026** | Prototype-oriented contrastive mean-teacher for unsupervised domain adaptive object detection | Scientific Reports |
| **2025** | Attention-Based Class-Conditioned Alignment for Multi-Source Domain Adaptation of Object Detectors | WACV |
| **2025** | DATR: Unsupervised Domain Adaptive Detection Transformer With Dataset-Level Adaptation | IEEE TIP |
| **2025** | Differential Alignment for Domain Adaptive Object Detection | AAAI |
| **2025** | Domain-Invariant Progressive Knowledge Distillation for UAV-Based Object Detection | IEEE GRSL |
| **2025** | Ensemble of Experts for Multi-Source Unsupervised Domain Adaptation in 3D Object Detection | IEEE Journals |
| **2025** | RT-DATR: Real-time Unsupervised Domain Adaptive Detection Transformer with Adversarial Feature Learning | arXiv |
| **2025** | Scale-Consistent and Temporally Ensembled Unsupervised Domain Adaptation for Object Detection | Sensors |
| **2024** | Unsupervised Video Domain Adaptation with Masked Pre-Training and Collaborative Self-Training | CVPR |
| **2024** | Controllable Prompt Tuning For Balancing Group Distributional Robustness | ICML |
| **2024** | Enhancing Domain Adaptation through Prompt Gradient Alignment | NeurIPS |
| **2024** | CMDA: Cross-Modal and Domain Adversarial Adaptation for LiDAR-Based 3D Object Detection | AAAI |
| **2024** | Collaborative Learning for Multi-Source Domain Adaptative Object Detection | NNICE |
| **2024** | DANE: A Dual-Level Alignment Network With Ensemble Learning for Multisource Domain Adaptation | IEEE TIM |
| **2024** | Diverse Feature-Level Guidance Adjustments for Unsupervised Domain Adaptative Object Detection | Applied Sciences |
| **2024** | Domain Adaptation for Large-Vocabulary Object Detectors | arXiv |
| **2024** | Empowering Unsupervised Domain Adaptation with Large-scale Pre-trained Vision-Language Models | WACV |
| **2024** | JFDI: Joint Feature Differentiation and Interaction for domain adaptive object detection | Neural Networks |
| **2024** | Mean teacher DETR with masked feature alignment: a robust domain adaptive detection framework | AAAI |
| **2024** | Multi-Source Domain Adaptation for Object Detection with Prototype-based Mean Teacher | WACV |
| **2024** | Robust Domain Adaptive Object Detection With Unified Multi-Granularity Alignment | IEEE TPAMI |
| **2024** | Towards Discriminability with Distribution Discrepancy Constrains for Multisource Domain Adaptation | Mathematics |
| **2024** | Unsupervised Domain-Adaptive Object Detection via Localization Regression Alignment | IEEE TNNLS |
| **2024** | Unsupervised Concept Drift Detection from Deep Learning Representations in Real-time | TKDE |
| **2024** | Concept drift adaptation with continuous kernel learning | Information Sciences |
| **2024** | VLDadaptor: Domain Adaptive Object Detection With Vision-Language Model Distillation | IEEE TMM |
| **2023** | POUF: Prompt-oriented unsupervised fine-tuning for large pre-trained models | ICML |
| **2023** | CoNMix for Source-free Single and Multi-target Domain Adaptation | WACV |
| **2023** | Contrastive Mean Teacher for Domain Adaptive Object Detectors | CVPR |
| **2023** | DaFKD: Domain-aware Federated Knowledge Distillation | CVPR |
| **2023** | Decompose to Adapt: Cross-Domain Object Detection Via Feature Disentanglement | IEEE TMM |
| **2023** | Disentangled Discriminator for Unsupervised Domain Adaptation on Object Detection | IROS |
| **2023** | Instance Relation Graph Guided Source-Free Domain Adaptive Object Detection | CVPR |
| **2023** | Learning Domain-Aware Detection Head with Prompt Tuning | NeurIPS |
| **2023** | Masked Retraining Teacher-Student Framework for Domain Adaptive Object Detection | ICCV |
| **2023** | MIC: Masked Image Consistency for Context-Enhanced Domain Adaptation | CVPR |
| **2023** | SPA: A Graph Spectral Alignment Perspective for Domain Adaptation | NeurIPS |
| **2022** | Reusing the Task-specific Classifier as a Discriminator: Discriminator-free Adversarial DA | CVPR |
| **2022** | A Closer Look at Smoothness in Domain Adversarial Training | ICML |
| **2022** | C2FDA: Coarse-to-Fine Domain Adaptation for Traffic Object Detection | IEEE TITS |
| **2022** | Exploring Sequence Feature Alignment for Domain Adaptive Detection Transformers | arXiv |
| **2022** | Incremental multi-target domain adaptation for object detection with efficient domain transfer | Pattern Recognition |
| **2022** | RFA-Net: Reconstructed Feature Alignment Network for Domain Adaptation Object Detection | IEEE JSTARS |
| **2022** | Discrepancy-Based Active Learning for Domain Adaptation | Arxiv |
| **2021** | ToAlign: Task-oriented Alignment for Unsupervised Domain Adaptation | NeurIPS |
| **2021** | Adversarial Unsupervised Domain Adaptation With Conditional and Label Shift | ICCV |
| **2021** | Cross-Domain Gradient Discrepancy Minimization for Unsupervised Domain Adaptation | CVPR |
| **2021** | Domain Adaptation With Auxiliary Target Domain-Oriented Classifier | CVPR |
| **2021** | MetaAlign: Coordinating Domain Alignment and Classification for Unsupervised DA | CVPR |
| **2021** | Active Universal Domain Adaptation | ICCV |
| **2021** | mDALU: Multi-Source Domain Adaptation and Label Unification With Partial Datasets | ICCV |
| **2021** | Multi-Target Domain Adaptation with Collaborative Consistency Learning | CVPR |
| **2021** | Cycle Self-Training for Domain Adaptation | NeurIPS |
| **2021** | ST3D: Self-training for Unsupervised Domain Adaptation on 3D Object Detection | CVPR |
| **2021** | SimROD: A Simple Adaptation Method for Robust Object Detection | ICCV |
| **2020** | Instance Adaptive Self-Training for Unsupervised Domain Adaptation | ECCV |
| **2020** | Classes Matter: A Fine-grained Adversarial Approach to Cross-domain Semantic Segmentation | ECCV |
| **2020** | Label Propagation with Augmented Anchors: A Simple SSL baseline for UDA | ECCV |
| **2020** | Domain Adaptive Semantic Segmentation Using Weak Labels | ECCV |
| **2020** | Domain Aggregation Networks for Multi-Source Domain Adaptation | ICML |
| **2020** | Learning to Combine: Knowledge Aggregation for Multi-Source Domain Adaptation | ECCV |
| **2020** | Do We Really Need to Access the Source Data? Source Hypothesis Transfer (SHOT) | ICML |
| **2020** | Domain Conditioned Adaptation Network | AAAI |
| **2020** | HoMM: Higher-order Moment Matching for Unsupervised Domain Adaptation | AAAI |
| **2020** | Open Compound Domain Adaptation | CVPR |
| **2020** | Cross-domain Object Detection through Coarse-to-Fine Feature Adaptation | CVPR |
| **2020** | Exploring Categorical Regularization for Domain Adaptive Object Detection | CVPR |
| **2020** | Progressive Domain Adaptation for Object Detection | WACV |
| **2020** | Gradually Vanishing Bridge for Adversarial Domain Adaptation | CVPR |
| **2020** | Implicit Class-Conditioned Domain Alignment for Unsupervised Domain Adaptation | ICML |
| **2020** | Discriminative Adversarial Domain Adaptation | AAAI |
| **2019** | Adapting Object Detectors via Selective Cross-Domain Alignment | CVPR |
| **2019** | Automatic Adaptation of Object Detectors to New Domains Using Self-Training | CVPR |
| **2019** | Sliced Wasserstein Discrepancy for Unsupervised Domain Adaptation | CVPR |
| **2019** | Semi-Supervised Domain Adaptation via Minimax Entropy | ICCV |
| **2019** | A Robust Learning Approach to Domain Adaptive Object Detection | ICCV |
| **2019** | Moment Matching for Multi-Source Domain Adaptation | ICCV |
| **2019** | Cycle-consistent Conditional Adversarial Transfer Networks | ACM MM |
| **2019** | Domain-Symmetric Networks for Adversarial Domain Adaptation | CVPR |
| **2018** | Conditional Adversarial Domain Adaptation (CDAN) | NIPS |
| **2018** | CyCADA: Cycle-Consistent Adversarial Domain Adaptation | ICML |
| **2018** | Maximum Classifier Discrepancy for Unsupervised Domain Adaptation | CVPR |
| **2018** | Adversarial Multiple Source Domain Adaptation (MDAN) | NIPS |
| **2018** | Generate To Adapt: Aligning Domains using Generative Adversarial Networks | CVPR |
| **2018** | Domain Adaptive Faster R-CNN for Object Detection in the Wild | arXiv |
| **2018** | Cross-Domain Weakly-Supervised Object Detection Through Progressive Domain Adaptation | CVPR |
| **2018** | Transferable Representation Learning with Deep Adaptation Networks | TPAMI |
| **2017** | Central Moment Discrepancy for Unsupervised Domain Adaptation | ICLR |
| **2017** | Deep Transfer Learning with Joint Adaptation Networks | ICML |
| **2017** | Adversarial Discriminative Domain Adaptation (ADDA) | CVPR |
| **2016** | Deep CORAL: Correlation Alignment for Deep Domain Adaptation | ECCV |
| **2016** | Unsupervised Domain Adaptation with Residual Transfer Networks | NIPS |
| **2016** | Domain-Adversarial Training of Neural Networks (DANN) | JMLR |
| **2015** | Learning Transferable Features with Deep Adaptation Networks (DAN) | ICML |
| **2014** | Deep Domain Confusion: Maximizing for Domain Invariance | Arxiv |
| **2011** | What you saw is not what you get: Domain adaptation using asymmetric kernel transforms | CVPR |
