---
title: "Where to go? Predicting next location in IoT environment"
collection: publications
permalink: /publication/2019-09-12-wheretogo_fcs
excerpt: 'This paper is about the location prediction, using Joint Modeling of Trajectory and Signal Sequence.'
date: 2019-09-12
venue: 'Frontiers of Computer Science'
paperurl: 'https://link.springer.com/article/10.1007/s11704-019-9118-9'
citation: 'Lin, Hao, et al. "Where to go? Predicting next location in IoT environment." Frontiers of Computer Science 15.1 (2020): 1-13.'
---
Abstract
======
Next location prediction has aroused great interests in the era of Internet of Things (IoT). With the ubiquitous deployment of sensor devices, e.g., GPS and Wi-Fi, IoT environment offers new opportunities for proactively analyzing human mobility patterns and predicting user’s future visit in low cost, no matter outdoor and indoor. In this paper, we consider the problem of next location prediction in IoT environment via a session-based manner. We suggest that user’s future intention in each session can be better inferred for more accurate prediction if patterns hidden inside both trajectory and signal sequences collected from IoT devices can be jointly modeled, which however existing state-of-the-art methods have rarely addressed. To this end, we propose a Trajectory and SIgnal Sequence (TSIS) model, where the trajectory transition regularities and signal temporal dynamics are jointly embedded in a neural network based model. Specifically, we employ Gated Recurrent Unit (GRU) for capturing the temporal dynamics in the multivariate signal sequence. Moreover, we adapt gated Graph Neural Networks (gated GNNs) on location transition graphs to explicitly model the transition patterns of trajectories. Finally, both the low-dimensional representations learned from trajectory and signal sequence are jointly optimized to construct a session embedding, which is further employed to predict the next location. Extensive experiments on two real-world Wi-Fi based mobility datasets demonstrate that TSIS is effective and robust for next location prediction compared with other competitive baselines.

Get the paper
======
+ **Download paper Here:** [click](http://mysteriouslfz.github.io/files/2019-09-12-wheretogo_fcs/Where_to_go_Predicting_next_location_in_IoT_environment.pdf)