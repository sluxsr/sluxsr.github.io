---
layout: default
title: Home
---

## Publications

<img align="center" src="https://github.com/sluxsr/sluxsr.github.io/blob/master/pics/eig_figure1.png?raw=true">

**Shengyao Lu**, Bang Liu, Keith G Mills, Jiao He, Di Niu, *EiG-Search: Generating Edge-Induced Subgraphs for GNN Explanation in Linear Time*

[ICML 2024](https://openreview.net/forum?id=HO0g6cHVZx) [[Paper](https://arxiv.org/pdf/2405.01762)] [[Code](https://github.com/sluxsr/EiG-Search)]

In this paper, we reveal that inducing subgraph explanations by edges is more comprehensive than other subgraph inducing techniques. We also emphasize the need of determining the subgraph explanation size for each data instance, as different data instances may involve different important substructures. Building upon these considerations, we introduce a training-free approach, named EiG-Search. We employ an efficient linear-time search algorithm over the edge-induced subgraphs, where the edges are ranked by an enhanced gradient-based importance. 

- - -

Keith G Mills, Fred X. Han, Mohammad Salameh, **Shengyao Lu**, Chunhua Zhou, Jiao He, Fengyu Sun, Di Niu, *Building Optimal Neural Architectures using Interpretable Knowledge*

[CVPR 2024](https://openreview.net/forum?id=ZPCqYkEyLW) [[Paper](https://arxiv.org/pdf/2403.13293)]

We propose AutoBuild, a scheme which learns to align the latent embeddings of operations and architecture modules with the ground-truth performance of the architectures they appear in. By doing so, AutoBuild is capable of assigning interpretable importance scores to architecture modules, such as individual operation features and larger macro operation sequences such that high-performance neural networks can be constructed without any need for search. 

- - -

<img align="center" src="https://github.com/sluxsr/sluxsr.github.io/blob/master/pics/goat_overview.png?raw=true">

**Shengyao Lu**, Keith G. Mills, Jiao He, Bang Liu, Di Niu, *GOAt: Explaining Graph Neural Networks via Graph Output Attribution*

[ICLR 2024](https://openreview.net/forum?id=2Q8TZWAHv4) [[Paper](https://arxiv.org/pdf/2401.14578)] [[Code](https://github.com/sluxsr/GOAt)]

We introduce Graph Output Attribution (GOAt), a novel method to attribute graph outputs to input graph features, creating GNN explanations that are faithful, discriminative, as well as stable across similar samples. By expanding the GNN as a sum of scalar products involving node features, edge features and activation patterns, we propose an efficient analytical method to compute contribution of each node or edge feature to each scalar product and aggregate the contributions from all scalar products in the expansion form to derive the importance of each node and edge. 

- - - 

<img align="center" src="https://github.com/sluxsr/sluxsr.github.io/blob/master/pics/r5_overview.png?raw=true">

**Shengyao Lu**\*, Bang Liu\*, Keith G. Mills, Shangling Jui, Di Niu, *R5: Rule Discovery with Reinforced and Recurrent Relational Reasoning*

[ICLR 2022 (Spotlight)](https://openreview.net/forum?id=2eXhNpHeW6E) [[Paper](https://arxiv.org/pdf/2205.06454)] [[Code](https://github.com/sluxsr/r5_graph_reasoning)]

We propose R5, a relational reasoning framework based on reinforcement learning that reasons over relational graph data and explicitly mines underlying compositional logical rules from observations. R5 has strong systematicity and being robust to noisy data. It consists of a policy value network equipped with Monte Carlo Tree Search to perform recurrent relational prediction and a backtrack rewriting mechanism for rule mining. By alternately applying the two components, R5 progressively learns a set of explicit rules from data and performs explainable and generalizable relation prediction. 


<br> 

## New Preprints

**Shengyao Lu**, Jiuding Yang, Baochun Li, Di Niu, *STExplainer: Global Explainability of GNNs via Frequent SubTree Mining*

[Under review]()

In this paper, we follow the intrinsic message-passing mechanism of typical GNNs and introduce a novel method for extracting global GNN explanations with rooted subtrees. Our approach not only facilitates quantitative assessment of the relative importance of significant subtree patterns but also enables rapid evaluations through straightforward lookups to determine the applicability of learned global concepts to new instances. Moreover, we offer an extension to extract subgraph global explanations by clustering the learned subtree patterns, providing a more comprehensive perspective on GNN behaviors.
