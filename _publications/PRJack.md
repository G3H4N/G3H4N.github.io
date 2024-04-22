---
title: "PRJack: Pruning-Resistant Model Hijacking Attack Against Deep Learning Models"
collection: publications
permalink: /publication/PRJack
excerpt:
date: 2024-06-30
venue: 'The International Joint Conference on Neural Networks (IJCNN)'
paperurl:
citation:
---
<b>Ge Han</b>, Zheng Li, Shanqing Guo

Deep learning models, pivotal in AI applications, are susceptible to model hijacking attacks.
In model hijacking attacks, adversaries can misuse models for unintended tasks, shifting blame and maintenance costs onto the models' deployers.
Existing attack methods re-purpose target models by poisoning their training sets during training.
However, leading models like GPT-4 and BERT with vast parameters are often pruned before deployment on resource-limited devices, which presents challenges for in-training attacks, including existing model hijacking attacks.
In this paper, we propose \texttt{PRJack}, the first pruning-resistant hijacking attack.
Specifically, the adversary re-purposes a model to perform a hijacking task different from the original task, which can still be activated even after model pruning.
Our experiments across multiple datasets and pruning techniques highlight \texttt{PRJack}'s remarkable superiority on pruned models over existing model hijacking attacks.

Download paper here ([PDF](http://g3h4n.github.io/files/PRJack.pdf)).
