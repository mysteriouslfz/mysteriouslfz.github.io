---
title: "Memory-Tuning: A Unified Parameter-Efficient Tuning Method for Pre-Trained Language Models"
collection: publications
permalink: /publication/2024-11-27-Memory-Tuning_TASLP
excerpt: 'We propose memory-tuning, a novel parameter-efficient method that unifies task-specific knowledge learning for both multi-head attention and feed-forward networks in Transformers, theoretically linking it to prefix tuning while outperforming full fine-tuning on eight benchmarks across sentence- and token-level tasks.'
date: 2024-11-27
venue: 'IEEE Transactions on Audio, Speech and Language Processing'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10769026'
citation: 'Qi, W., Liu, R., Zuo, Y., Li, F., Chen, Y., & Wu, J. (2024). Memory-Tuning: A Unified Parameter-Efficient Tuning Method for Pre-trained Language Models. IEEE/ACM Transactions on Audio, Speech, and Language Processing.'
---
Abstract
======
Conventional fine-tuning encounters increasing difficulties given the size of current Pre-trained Language Models, which makes parameter-efficient tuning become the focal point of frontier research. Recent advances in this field is the unified tuning methods that aim to tune the representations of both multi-head attention (MHA) and fully connected feed-forward network (FFN) simultaneously, but they rely on existing tuning methods and do not explicitly model domain knowledge for downstream tasks. In this work, we propose memory-tuning, a novel unified parameter-efficient tuning method with task-specific knowledge learning, for both MHA and FFN components in Transformer blocks. We also prove that the well-known prefix tuning is also a kind of memory tuning, which further ensures memory tuning is a genuine unified tuning method. Experiments on eight benchmark data sets including both sentence- and token-level tasks demonstrate that our method outperforms the state-of-the-art baselines even full-tuning in most cases.

Get the paper
======
+ **Download paper Here:** [click](http://mysteriouslfz.github.io/files/2024-11-27-Memory-Tuning_TASLP/Memory-Tuning_A_Unified_Parameter-Efficient_Tuning_Method_for_Pre-Trained_Language_Models.pdf)