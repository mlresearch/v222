---
abstract: The introduction of the generative adversarial imitation learning (GAIL)
  algorithm has spurred the development of scalable imitation learning approaches
  using deep neural networks. Many of the algorithms that followed used a similar
  procedure, combining on-policy actor-critic algorithms with inverse reinforcement
  learning. More recently there have been an even larger breadth of approaches, most
  of which use off-policy algorithms. However, with the breadth of algorithms, everything
  from datasets to base reinforcement learning algorithms to evaluation settings can
  vary, making it difficult to fairly compare them. In this work we re-implement 6
  different IL algorithms, updating 3 of them to be off-policy, base them on a common
  off-policy algorithm (SAC), and evaluate them on a widely-used expert trajectory
  dataset (D4RL) for the most common benchmark (MuJoCo). After giving all algorithms
  the same hyperparameter optimisation budget, we compare their results for a range
  of expert trajectories. In summary, GAIL, with all of its improvements, consistently
  performs well across a range of sample sizes, AdRIL is a simple contender that performs
  well with one important hyperparameter to tune, and behavioural cloning remains
  a strong baseline when data is more plentiful.
section: Contributed Papers
title: A Pragmatic Look at Deep Imitation Learning
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: arulkumaran24a
month: 0
tex_title: A Pragmatic Look at Deep Imitation Learning
firstpage: 58
lastpage: 73
page: 58-73
order: 58
cycles: false
bibtex_author: Arulkumaran, Kai and Ogawa Lillrank, Dan
author:
- given: Kai
  family: Arulkumaran
- given: Dan
  family: Ogawa Lillrank
date: 2024-02-27
address:
container-title: Proceedings of the 15th Asian Conference on Machine Learning
volume: '222'
genre: inproceedings
issued:
  date-parts:
  - 2024
  - 2
  - 27
pdf: https://proceedings.mlr.press/v222/arulkumaran24a/arulkumaran24a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
