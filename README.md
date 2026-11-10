# Gal Wertheizer

ML researcher and engineer. I work on the safety and interpretability of large
models: adversarial robustness of LLMs, mechanistic interpretability of
generative models, and learning on relational data.

Contact: wertheizer@campus.technion.ac.il · Models: [huggingface.co/galwert](https://huggingface.co/galwert)

## Featured: AnchorRep (NeurIPS 2026)

**[AnchorRep](https://github.com/galwert/AnchorRep)**: a defense against
cross-model jailbreak transfer. A lightweight LoRA adapter pushes the defended
model's internal representations of harmful prompts away from a frozen anchor
model, cutting cross-model adversarial transfer to under 2% on five open-weight
LLMs without attack-specific training. Full training and evaluation code,
configs, attack artifacts and audit logs, plus five trained adapters on
[Hugging Face](https://huggingface.co/galwert).

## Research projects

| Repository | What it is |
|---|---|
| [sam3d-mechanistic-interpretability](https://github.com/galwert/sam3d-mechanistic-interpretability) | Sparse autoencoders, circuit discovery and activation steering inside SAM 3D Objects, a 1.2B image-to-3D generator. Finds a three-feature circuit controlling geometry and shows object identity is not linearly represented. |
| [structml-relational-gnn-ablations](https://github.com/galwert/structml-relational-gnn-ablations) | Ablation study of relational GNNs on RelBench: edge directionality, heterogeneity, column encoders and depth. |
| [backdoor-defense-quantization](https://github.com/galwert/backdoor-defense-quantization) | Do backdoor defenses survive quantization? Four defenses, three quantization schemes, both orderings, on DistilBERT. |

## Hackathon

**[sar-voidcrawler](https://github.com/galwert/sar-voidcrawler)**: navigation and perception stack for a search-and-rescue crawler robot. Synthetic LiDAR SLAM, goal-directed navigation with a 360 degree survivor scan, human-part LiDAR segmentation, and SAM2-based rubble analysis, all runnable on CPU without a robot.

## Coursework (Technion)

| Course | Repository | What's inside |
|---|---|---|
| 236605 Structured Machine Learning | [236605-structured-ml](https://github.com/galwert/236605-structured-ml) | Relational feature extraction and node embeddings on RelBench. Final project: [structml-relational-gnn-ablations](https://github.com/galwert/structml-relational-gnn-ablations) |
| 048954 Statistical Methods in Image Processing | [048954-statistical-methods-image-processing](https://github.com/galwert/048954-statistical-methods-image-processing) | Normalizing flows, energy-based models, score matching |
| 236299 Introduction to NLP | [236299-intro-to-nlp](https://github.com/galwert/236299-intro-to-nlp) | Text classification, slot-filling taggers, CKY parsing, semantic parsing for QA |
| 236360 Theory of Compilation | [236360-theory-of-compilation](https://github.com/galwert/236360-theory-of-compilation) | A compiler for a C-like language, from flex lexer to LLVM IR with backpatching |
| 234123 Operating Systems | [234123-operating-systems](https://github.com/galwert/234123-operating-systems) | `smash`, a Linux shell in C++ with job control, pipes and signals |
| 234218 Data Structures 1 | [234218-data-structures-1](https://github.com/galwert/234218-data-structures-1) | AVL and rank-augmented trees, union-find, five wet assignments |
| 234124 Introduction to Systems Programming | [234124-intro-to-systems-programming](https://github.com/galwert/234124-intro-to-systems-programming) | C++ templates, iterators, exceptions, a turn-based game |
| 234118 Computer Organization | [234118-computer-organization](https://github.com/galwert/234118-computer-organization) | x86-64 assembly with raw Linux syscalls |
| Computer architecture | [computer-architecture-simulators](https://github.com/galwert/computer-architecture-simulators) | Cache hierarchy and branch predictor simulators |
