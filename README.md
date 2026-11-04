# Gal Wertheizer

ML researcher and engineer. I work on the safety and interpretability of large
models: adversarial robustness of LLMs, mechanistic interpretability of
generative models, and learning on relational data.

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

## Coursework

| Repository | Topic |
|---|---|
| [structml-assignments](https://github.com/galwert/structml-assignments) | Relational feature extraction and node embeddings |
| [stat-methods-image-processing](https://github.com/galwert/stat-methods-image-processing) | Normalizing flows, energy-based models, score matching |
| [computer-architecture-simulators](https://github.com/galwert/computer-architecture-simulators) | Cache hierarchy and branch predictor simulators |
| [smash-linux-shell](https://github.com/galwert/smash-linux-shell) | `smash`, a Linux shell in C++ with job control, pipes and signals |
| [fanc-compiler-1-lexer](https://github.com/galwert/fanc-compiler-1-lexer), [2-parser](https://github.com/galwert/fanc-compiler-2-parser), [3-semantics](https://github.com/galwert/fanc-compiler-3-semantics), [5-llvm-codegen](https://github.com/galwert/fanc-compiler-5-llvm-codegen) | A compiler for a C-like language, from flex scanner to LLVM IR |
| [avl-tree-company-db](https://github.com/galwert/avl-tree-company-db), [rank-tree-union-find](https://github.com/galwert/rank-tree-union-find) | AVL trees, rank-augmented trees and union-find in C++ |
| [x86-64-assembly-hamming](https://github.com/galwert/x86-64-assembly-hamming) | x86-64 assembly with raw Linux syscalls |
| [nlp-text-classification](https://github.com/galwert/nlp-text-classification), [nlp-sequence-labeling](https://github.com/galwert/nlp-sequence-labeling), [nlp-cky-parser](https://github.com/galwert/nlp-cky-parser), [nlp-semantic-parsing](https://github.com/galwert/nlp-semantic-parsing) | NLP course projects: text classifiers, slot-filling taggers, CKY parsing, semantic parsing |
