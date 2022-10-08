---
title: "FuzzGAN: A Generation-Based Fuzzing Framework For Testing Deep Neural Networks"
collection: publications
permalink: /publication/FuzzGAN
excerpt:
date: 2022
venue: '(Under Review) The 24th IEEE International Conference on High Performance Computing and Communications (HPCC 2022)'
paperurl:
citation: 
---
<b>Ge Han</b>, Zheng Li, Peng Tang, Chengyu Hu, Shanqing Guo

Deep neural networks (DNNs) are increasingly deployed in various fields.
Despite their spectacular advances, DNNs are known to suffer from adversarial vulnerabilities.
The robustness of DNNs is then threatened by leading them to misclassifications with unexpected inputs (adversarial examples).
The fuzzing technique frequently used for testing traditional software has recently been adopted to evaluate the robustness of DNNs.
Current DNN fuzzing techniques focus on image classification DNNs and generate test cases by mutations, e.g., image transformations and adversarial perturbations.
However, mutation-based test cases usually lack diversity and have distribution deflection from the original DNN input space, which impacts the evaluation of DNNs.

In this paper, we propose a generation-based fuzzing framework FuzzGAN to detect adversarial flaws existing in DNNs.
We integrate the testing purpose and the guidance of the neuron coverage into the original objectives of auxiliary classifier generative adversarial networks.
Hence, FuzzGAN learns the representation of a DNN's input space and generates test cases without the limitation of any concrete seed input.
We evaluate the performance of FuzzGAN on two DNN models that have classical network structures and are trained on public datasets.
The experiment results demonstrate that FuzzGAN can generate realistic, diverse and valid test cases and achieve high neuron coverage.
Moreover, these test cases can be used to improve the performance of the target DNN through adversarial retraining.

Download paper here ([PDF](http://g3h4n.github.io/files/FuzzGAN.pdf)).
