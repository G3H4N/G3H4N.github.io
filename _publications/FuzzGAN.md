---
title: "FuzzGAN: A Generation-Based Fuzzing Framework For Testing Deep Neural Networks"
collection: publications
permalink: /publication/FuzzGAN
excerpt:
date: 2019-10-28
venue: '(Under Review) The 24th IEEE International Conference on High Performance Computing and Communications (HPCC 2022)'
paperurl:
citation: 
---
<b>Ge Han</b>, Zheng Li, Peng Tang, Chengyu Hu, Shanqing Guo

Deep neural networks (DNNs) are increasingly de- ployed in a wide variety of fields. Despite their spectacular advances, DNNs are known to suffer from various vulnerabilities. Similar to traditional software, one of the most common DNN vulnerabilities relates to the hidden defects that allow unexpected inputs (adversarial examples) lead a DNN to incorrect classifi- cations. Fuzzing technique has been frequently used to evaluate traditional software and it is also a way to effectively discover potential defects hidden within a DNN. In this paper, we propose a generation-based fuzzing framework FuzzGAN to detect the defects existing in DNNs. Rather than the mutation-based fuzzing that tests DNNs with mutated seed inputs, FuzzGAN generates test cases from random noise under the guidance of some coverage criterion, without the limitation of concrete seeds. We take neuron coverage as our criterion to measure the adequacy of the fuzzing and investigate the effectiveness of FuzzGAN on two DNN models that are with classical network structures and trained on public datasets. The experiment demonstrates that FuzzGAN can generate realistic and valid test cases and achieve a high neuron coverage. Moreover, these test cases can be used to improve the performance of the target DNN through adversarial retraining.

Download paper here ([PDF](http://g3h4n.github.io/files/FuzzGAN.pdf)).
