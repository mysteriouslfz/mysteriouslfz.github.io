---
title: "Beyond One-Size-Fits-All: Adaptive Subgraph Denoising for Zero-Shot Graph Learning with Large Language Models"
collection: publications
permalink: /publication/2026-03-03-GraphSSR_SIGKDD_2026
excerpt: 'To address the noise and suboptimality of fixed subgraph extraction in zero-shot graph reasoning, we propose GraphSSR, a framework that utilizes a "Sample-Select-Reason" (SSR) pipeline, supervised fine-tuning (SSR-SFT), and reinforcement learning (SSR-RL) to enable Large Language Models to adaptively extract and denoise task-relevant graph structures for superior generalization.'
date: 2026-03-03
venue: 'SIGKDD'
paperurl: 'https://arxiv.org/abs/2603.02938'
citation: 'Li, F., Zhang, L., Zuo, Y., Zhao, R., Liu, Y., Ma, Y., ... & Feng, J. (2026). Beyond One-Size-Fits-All: Adaptive Subgraph Denoising for Zero-Shot Graph Learning with Large Language Models. arXiv preprint arXiv:2603.02938.'
---
Abstract
======
Graph-based tasks in the zero-shot setting remain a significant challenge due to data scarcity and the inability of traditional Graph Neural Networks (GNNs) to generalize to unseen domains or label spaces. While recent advancements have transitioned toward leveraging Large Language Models (LLMs) as predictors to enhance GNNs, these methods often suffer from cross-modal alignment issues. A recent paradigm (i.e., Graph-R1) overcomes the aforementioned architectural dependencies by adopting a purely text-based format and utilizing LLM-based graph reasoning, showing improved zero-shot generalization. However, it employs a task-agnostic, one-size-fits-all subgraph extraction strategy, which inevitably introduces significant structural noise--irrelevant neighbors and edges--that distorts the LLMs' receptive field and leads to suboptimal predictions. To address this limitation, we introduce GraphSSR, a novel framework designed for adaptive subgraph extraction and denoising in zero-shot LLM-based graph reasoning. Specifically, we propose the SSR pipeline, which dynamically tailors subgraph extraction to specific contexts through a "Sample-Select-Reason" process, enabling the model to autonomously filter out task-irrelevant neighbors and overcome the one-size-fits-all issue. To internalize this capability, we develop SSR-SFT, a data synthesis strategy that generates high-quality SSR-style graph reasoning traces for supervised fine-tuning of LLMs. Furthermore, we propose SSR-RL, a two-stage reinforcement learning framework that explicitly regulates sampling and selection operations within the proposed SSR pipeline designed for adaptive subgraph denoising. By incorporating Authenticity-Reinforced and Denoising-Reinforced RL, we guide the model to achieve accurate predictions using parsimonious, denoised subgraphs for reasoning.

Get the paper
======
+ **Download paper Here:** [click](http://mysteriouslfz.github.io/files/2026-03-03-GraphSSR_SIGKDD_2026/Beyond_One-Size-Fits-All_Adaptive_Subgraph_Denoising_for_Zero-Shot_Graph_Learning_with_Large_Language_Models.pdf)