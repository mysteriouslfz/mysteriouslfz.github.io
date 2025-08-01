---
title: "LLMs as Zero-shot Graph Learners: Alignment of GNN Representations with LLM Token Embeddings"
collection: publications
permalink: /publication/2024-09-26-TEA-GLM-NeurIPS_2024
excerpt: 'We propose TEA-GLM, a zero-shot graph learning framework that aligns GNN representations with LLM token embeddings via a fixed linear projector, enabling cross-task and cross-dataset generalization without LLM fine-tuning.'
date: 2024-09-26
venue: '38th Conference on Neural Information Processing Systems (NeurIPS 2024)'
paperurl: 'https://proceedings.neurips.cc/paper_files/paper/2024/file/0b77d3a82b59e9d9899370b378087faf-Paper-Conference.pdf'
citation: 'Wang, D., Zuo, Y., Li, F., & Wu, J. (2024). Llms as zero-shot graph learners: Alignment of gnn representations with llm token embeddings. Advances in Neural Information Processing Systems, 37, 5950-5973.'
---
Abstract
======
Zero-shot graph machine learning, especially with graph neural networks (GNNs), has garnered significant interest due to the challenge of scarce labeled data. While methods like self-supervised learning and graph prompt learning have been extensively explored, they often rely on fine-tuning with task-specific labels, limiting their effectiveness in zero-shot scenarios. Inspired by the zero-shot capabilities of instruction-fine-tuned large language models (LLMs), we introduce a novel framework named Token Embedding-Aligned Graph Language Model (TEA-GLM) that leverages LLMs as cross-dataset and cross-task zero-shot learners for graph machine learning. Concretely, we pretrain a GNN, aligning its representations with token embeddings of an LLM. We then train a linear projector that transforms the GNN’s representations into a fixed number of graph token embeddings without tuning the LLM. A unified instruction is designed for various graph tasks at different levels, such as node classification (node-level) and link prediction (edge-level). These design choices collectively enhance our method’s effectiveness in zero-shot learning, setting it apart from existing methods. Experiments show that our graph token embeddings help the LLM predictor achieve state-of-the-art performance on unseen datasets and tasks compared to other methods using LLMs as predictors. Our code is available at https://github.com/W-rudder/TEA-GLM.

Get the paper
======
+ **Download paper Here:** [click](http://mysteriouslfz.github.io/files/2024-09-26-TEA-GLM-NeurIPS_2024/NeurIPS-2024-llms-as-zero-shot-graph-learners-alignment-of-gnn-representations-with-llm-token-embeddings-Paper-Conference.pdf)