---
layout: default
title: Home
---

## Introduction 

**Shengyao Lu** (陆晟瑶) is an incoming Assistant Professor in the department of [Computer Science](https://www.uvic.ca/ecs/computerscience/index.php) (CS) at the [University of Victoria](https://www.uvic.ca) (UVic). She received her BSc. and Ph.D. degree at the [University of Alberta](https://www.ualberta.ca/en/index.html). Her research interests primarily lie in the areas of Explainbale AI (XAI), Graph Neural Networks (GNNs), theory and techniques for AGI (e.g., understanding and improving large language models via graphs, XAI and reinforcement learning (RL)).

<span style="color:#2858B5; font-weight: bold;">Openings:</span> I am looking for highly-motivated students starting Spring/Fall 2026. Please send me your CV if interested.

<br> 

## Selected Publications

Jiuding Yang, **Shengyao Lu**, Weidong Guo, Xiangyang Li, Kaitong Yang, Yu Xu, Di Niu. <span style="color:black">*TaCIE: Enhancing Instruction Comprehension in Large Language Models through Task-Centred Instruction Evolution*</span>.

[COLING 2025](https://coling2025.org/program/main_conference_papers/) [[Paper](https://arxiv.org/abs/2410.02795)]

Our innovative approach, Task-Centered Instruction Evolution (TaCIE), addresses these shortcomings by redefining instruction evolution from merely evolving seed instructions to a more dynamic and comprehensive combination of elements. TaCIE starts by deconstructing complex instructions into their fundamental components. It then generates and integrates new elements with the original ones, reassembling them into more sophisticated instructions that progressively increase in difficulty, diversity, and complexity. Applied across multiple domains, LLMs fine-tuned with these evolved instructions have substantially outperformed those tuned with conventional methods, marking a significant advancement in instruction-based model fine-tuning. 

- - -

<img align="center" src="https://github.com/sluxsr/sluxsr.github.io/blob/master/pics/eig_figure1.png?raw=true">

**Shengyao Lu**, Bang Liu, Keith G Mills, Jiao He, Di Niu. <span style="color:black">*EiG-Search: Generating Edge-Induced Subgraphs for GNN Explanation in Linear Time*</span>.

[ICML 2024](https://openreview.net/forum?id=HO0g6cHVZx) [[Paper](https://arxiv.org/pdf/2405.01762)] [[Code](https://github.com/sluxsr/EiG-Search)]

In this paper, we reveal that inducing subgraph explanations by edges is more comprehensive than other subgraph inducing techniques. We also emphasize the need of determining the subgraph explanation size for each data instance, as different data instances may involve different important substructures. Building upon these considerations, we introduce a training-free approach, named EiG-Search. We employ an efficient linear-time search algorithm over the edge-induced subgraphs, where the edges are ranked by an enhanced gradient-based importance. 

- - -

Keith G Mills, Fred X. Han, Mohammad Salameh, **Shengyao Lu**, Chunhua Zhou, Jiao He, Fengyu Sun, Di Niu. <span style="color:black">*Building Optimal Neural Architectures using Interpretable Knowledge*</span>.

[CVPR 2024](https://openreview.net/forum?id=ZPCqYkEyLW) [[Paper](https://arxiv.org/pdf/2403.13293)]

We propose AutoBuild, a scheme which learns to align the latent embeddings of operations and architecture modules with the ground-truth performance of the architectures they appear in. By doing so, AutoBuild is capable of assigning interpretable importance scores to architecture modules, such as individual operation features and larger macro operation sequences such that high-performance neural networks can be constructed without any need for search. 

- - -

<img align="center" src="https://github.com/sluxsr/sluxsr.github.io/blob/master/pics/goat_overview.png?raw=true">

**Shengyao Lu**, Keith G. Mills, Jiao He, Bang Liu, Di Niu. <span style="color:black">*GOAt: Explaining Graph Neural Networks via Graph Output Attribution*</span>.

[ICLR 2024](https://openreview.net/forum?id=2Q8TZWAHv4) [[Paper](https://arxiv.org/pdf/2401.14578)] [[Code](https://github.com/sluxsr/GOAt)] [[Video](https://iclr.cc/virtual/2024/poster/19551)]

We introduce Graph Output Attribution (GOAt), a novel method to attribute graph outputs to input graph features, creating GNN explanations that are faithful, discriminative, as well as stable across similar samples. By expanding the GNN as a sum of scalar products involving node features, edge features and activation patterns, we propose an efficient analytical method to compute contribution of each node or edge feature to each scalar product and aggregate the contributions from all scalar products in the expansion form to derive the importance of each node and edge. 

- - - 

<img align="center" src="https://github.com/sluxsr/sluxsr.github.io/blob/master/pics/r5_overview.png?raw=true">

**Shengyao Lu**\*, Bang Liu\*, Keith G. Mills, Shangling Jui, Di Niu. <span style="color:black">*R5: Rule Discovery with Reinforced and Recurrent Relational Reasoning*</span>.

[ICLR 2022 (Spotlight)](https://openreview.net/forum?id=2eXhNpHeW6E) [[Paper](https://arxiv.org/pdf/2205.06454)] [[Code](https://github.com/sluxsr/r5_graph_reasoning)] [[Video](https://iclr.cc/virtual/2022/spotlight/7054)]

We propose R5, a relational reasoning framework based on reinforcement learning that reasons over relational graph data and explicitly mines underlying compositional logical rules from observations. R5 has strong systematicity and being robust to noisy data. It consists of a policy value network equipped with Monte Carlo Tree Search to perform recurrent relational prediction and a backtrack rewriting mechanism for rule mining. By alternately applying the two components, R5 progressively learns a set of explicit rules from data and performs explainable and generalizable relation prediction. 

<br> 

## New Preprints

**Shengyao Lu**, Jiuding Yang, Baochun Li, Di Niu. <span style="color:black">*STExplainer: Global Explainability of GNNs via Frequent SubTree Mining*</span>.

[Under review]()

In this paper, we follow the intrinsic message-passing mechanism of typical GNNs and introduce a novel method for extracting global GNN explanations with rooted subtrees. Our approach not only facilitates quantitative assessment of the relative importance of significant subtree patterns but also enables rapid evaluations through straightforward lookups to determine the applicability of learned global concepts to new instances. Moreover, we offer an extension to extract subgraph global explanations by clustering the learned subtree patterns, providing a more comprehensive perspective on GNN behaviors.

<br>

## Academic services 
Reviewer of AAAI'26, NeurIPS'25, ICCV'25, ICML'25, CVPR'25, AISTATS'25, ICLR'25, AAAI'25, NeurIPS'24, CVPR'24, KDD'24. Journal: Neural Networks