---
title: "FragDroid: Automated User Interface Interaction with Activity and Fragment Analysis in Android Applications"
collection: publications
permalink: /publication/FragDroid
excerpt:
date: 2018-06-25
venue: '48th Annual IEEE/IFIP International Conference on Dependable Systems and Networks (DSN)'
paperurl:
citation: 
---
Jia Chen, <b>Ge Han</b>, Shanqing Guo, Wenrui Diao

Recent years have witnessed the enormous growth of Android phones in the consumer market. On the other hand, as the most popular mobile platform, Android also attracts lots of attackers' attention. As a result, more and more Android malicious apps appear in the wild, which poses a serious threat to user's security and privacy. To such massive volume of Android malware, automated UI testing techniques have become the mainstream solutions because of the detection efficiency and accuracy. However, all existing UI testing techniques treat the Activity as the basic unit of UI interactions and cannot carry out a fine-grained analysis for Fragments. Due to the lack of Fragment-level analysis, the path coverage is usually quite limited. To fill this gap, in this paper, we propose FragDroid, a novel automated UI testing framework supporting both Activity and Fragment analysis. To achieve the Fragment-level testing, we design the Activity & Fragment Transition Model (AFTM) to simulate the internal interactions of an app, and ATFM could be utilized to generate test cases automatically through UI interactions. With the assist of AFTM, FragDroid achieves accessing most Activities and Fragments contained in the app along with the capability of detecting arbitrary API calls. We implemented a prototype of FragDroid and evaluated it on 15 popular apps. The results show FragDroid successfully covered 66% Fragments and the corresponding API calls of testing apps. Also, the traditional approaches have to miss at least 9.6% of API calls invoked in Fragments.

[Download paper here](http://g3h4n.github.io/files/FragDroid.pdf)
