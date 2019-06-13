---
title: "Evaluation and integration of bit-sliced block ciphers"
collection: publications
permalink: /publication/MasterThesis
excerpt:
date: 2015-12-06
venue: '(Dissertation) University of Bristol, UK'
paperurl:
citation: 
---
<b>Ge Han</b>

Block ciphers are deterministic cryptographic algorithms processing data as blocks of fixed-length bits. The bitslice is a non-conventional implementation technique for block ciphers that data blocks are sliced in bit. The operation of a single slice influences all blocks where the bits on the slice come from. In this way, the processor works in a Single Instruction Multiple Data manner, and numerous data blocks are encrypted in parallel.
The aim of this project is studying bitslice technique from two perspectives: applying this non-conventional technique into the implementation of a chosen block cipher and evaluating its performance compared with the conventional version of implementation; assessing the feasibility of extending it based on Instruction Set Architectures (ISAs) to make it achieves better behaviours and/or integrating it to an existing cryptographic libraries for compatible usage by existing applications.
In this project Advanced Encryption Standard (AES) is selected for implementing and evaluating. The design of Instruction Set Extension (ISE) is based on a new version of Reduced Instruction Set Computing processor design strategy, RISC-V. To make the new implementation useful for general network applications, a popularly used cryptographic library OpenSSL is assessed for integration.
