---
title: "EiG-Search: Generating Edge-Induced Subgraphs for GNN Explanation in Linear Time"
author: shengyao
date: 2024-10-10 
categories: [Publications]
tags: [ICML, Publications]
---
<img align="center" src="commons/pics/eig_figure1.png">

**Shengyao Lu**, Bang Liu, Keith G Mills, Jiao He, Di Niu. 

[**ICML 2024**](https://openreview.net/forum?id=HO0g6cHVZx) [[Paper](https://arxiv.org/pdf/2405.01762)] [[Code](https://github.com/sluxsr/EiG-Search)]

In this paper, we reveal that inducing subgraph explanations by edges is more comprehensive than other subgraph inducing techniques. We also emphasize the need of determining the subgraph explanation size for each data instance, as different data instances may involve different important substructures. Building upon these considerations, we introduce a training-free approach, named EiG-Search. We employ an efficient linear-time search algorithm over the edge-induced subgraphs, where the edges are ranked by an enhanced gradient-based importance. 