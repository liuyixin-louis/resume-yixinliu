---
title: Conditional Automated Channel Pruning for Deep Neural Networks
subtitle: ""
publication_types:
  - "2"
authors:
  - Yixin Liu*
  - Yong Guo*
  - Jiaxin Guo
  - Luoqian Jiang
  - Jian Chen
publication_short: ""
abstract: Channel pruning has become one of the predominant compression methods
  to deploy deep models on resourceconstrained devices. Most channel pruning
  methods often use a fixed compression rate for all the layers of the model,
  which, however, may not be optimal. To address this issue, given a specific
  target compression rate, one can search for the optimal compression rate for
  each layer via some automated methods. Nevertheless, when we consider multiple
  compression rates, these methods have to repeat the channel pruning process
  multiple times, once for each rate, which can be unnecessary and inefficient.
  To tackle the problem, we propose a Conditional Automated Channel Pruning
  (CACP) method which simultaneously produces compressed models under different
  compression rates through a single channel pruning process. Specifically, CACP
  takes a set of compression rates and the original model as its input, and
  outputs the feasible compressed models that satisfy the considered compression
  rates. To learn CACP, we cast the layer-by-layer channel pruning process into
  a Markov decision process (MDP), in which we seek to solve a series of
  decision-making problems. Based on MDP, we develop a reinforcement learning
  (RL) framework with deep deterministic policy gradient (DDPG) to learn the
  optimal policy. To satisfy the constraint items in the optimization problem,
  we design a constraint-guaranteed method, which guides the agent to search for
  compressed models that satisfy the computational constraints by limiting the
  action space. Extensive experiments on CIFAR-10 and ImageNet datasets
  demonstrate the superiority of our method over existing methods.
draft: false
featured: true
projects: []
slides: ""
url_pdf: paper/cacp/cacp.pdf
summary: ""
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
author_notes: []
doi: ""
publication: Published in IEEE Signal Processing Letters
tags:
  - Source Themes
image:
  caption: ""
  focal_point: ""
  preview_only: false
  filename: featured.jpg
date: 2021-06-12T14:45:11.706Z
url_slides: ""
publishDate: 2017-01-01T00:00:00.000Z
url_poster: ""
url_code: "https://github.com/liuyixin-louis/CACPpruner"
---
