---
title: "BoostXML: Gradient Boosting for Extreme Multilabel Text Classification With Tail Labels"
collection: publications
permalink: /publication/2022-03-21-BoostXML_TNNLS
excerpt: 'We present BoostXML, a deep learning-based extreme multilabel text classification method enhanced by gradient boosting, which specifically improves tail-label prediction through a Boosting Step that optimizes residuals from unfitted tail-label instances, a Corrective Step to avoid optimization mismatches, and a Pretraining Step to balance label focus.'
date: 2023-06-26
venue: 'IEEE Transactions on Neural Networks and Learning Systems'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10161991'
citation: 'Li, F., Zuo, Y., Lin, H., & Wu, J. (2023). Boostxml: gradient boosting for extreme multilabel text classification with tail labels. IEEE Transactions on Neural Networks and Learning Systems, 35(11), 15292-15305.'
---
Abstract
======
Multilabel learning involving hundreds of thousands or even millions of labels is referred to as extreme multilabel learning (XML), in which the labels often follow a power-law distribution with the majority occurring in very few data points as tail labels. Recent years have witnessed the intensive use of deep-learning methods for high-performance XML, but they are typically optimized for the head labels with abundant training instances and less consider the performance on tail labels, which, however, like the needles in haystacks, are often the focus of attention in real-life applications. In light of this, we present BoostXML, a deep learning-based XML method for extreme multilabel text classification, enhanced greatly by gradient boosting. In BoostXML, we pay more attention to tail labels in each Boosting Step by optimizing the residual mostly from unfitted training instances with tail labels. A Corrective Step is further proposed to avoid the mismatching between the text encoder and weak learners during optimization, which reduces the risk of falling into local optima and improves model performance. A Pretraining Step is also introduced in the initial stage of BoostXML to avoid exorbitant bias to tail labels. Extensive experiments on five benchmark datasets with state-of-the-art baselines demonstrate the advantage of BoostXML in tail-label prediction.

Get the paper
======
+ **Download paper Here:** [click](http://mysteriouslfz.github.io/files/2023-06-26-BoostXML_TNNLS/BoostXML Gradient Boosting for Extreme Multi-label Text Classification With Tail Labels.pdf)