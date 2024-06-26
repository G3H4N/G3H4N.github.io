---
title: "Detection and Attribution of Models Trained on Generated Data"
collection: publications
permalink: /publication/GAN-trained
excerpt:
date: 2024-04-14
venue: 'IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)'
paperurl:
citation: 
---
<b>Ge Han</b>, Ahmed Salem, Zheng Li, Shanqing Guo, Michael Backes, Yang Zhang

Generative Adversarial Networks (GANs) have become widely used in model training, as they can improve performance and/or protect sensitive information by generating data.
However, this also raises potential risks, as malicious GANs may compromise or sabotage models by poisoning their training data.
Therefore, it is important to verify the origin of a model’s training data for accountability purposes.
In this work, we take the first step in the forensic analysis of models trained on GAN-generated data.
Specifically, we first detect whether a model is trained on GAN-generated or real data.
We then attribute these models, trained on GAN-generated data, to their respective source GANs.
We conduct extensive experiments on three datasets, using four popular GAN architectures and four common model architectures.
Empirical results show the remarkable performance of our detection and attribution methods.
Furthermore, we conduct a more in-depth study and reveal that models trained on various data sources exhibit different decision boundaries and behaviours.

Download paper here ([PDF](http://g3h4n.github.io/files/GAN_trained.pdf)).
