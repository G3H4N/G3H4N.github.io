---
title: "DeepKeyStego: Protecting Communication by Key-dependent Steganography with Deep Networks"
collection: publications
permalink: /publication/DeepKeyStego
excerpt:
date: 2019-08-10
venue: 'The 21st IEEE International Conferences on High Performance Computing and Communications (HPCC)'
paperurl:
citation: 
---
<b>Zheng Li, Ge Han, Shanqing Guo.</b>

Hiding both the presence and the content of secret information against eavesdropping over public communication channels is crucial for protecting privacy sensitive communica- tion. Steganography is the art of hiding confidential information into normal carriers. Images are the most widely used containers for steganography. However, most of the current popular image steganographic schemes are designed with prescribed human- based rules and can be effectively detected by existing steganalysis tools. Even though the steganography implemented by deep networks has a better performance against steganalysis to some extent, it is still exposed to a threat that an attacker with access to the decoding model can recover the embedded information from steganographic images.

Hence, we introduce the keys to the steganography based on deep networks and design symmetric and asymmetric stegano- graphic schemes where the embedded information will never be recovered without secret keys. We further propose DeepKeyStego, a framework training key-dependent steganographic models with novel network structures. Compared to previous meth- ods, DeepKeyStego based on novel network structures achieves excellent invisibility and produces a steganographic algorithm without any prescribed rules or hand-crafted features, which can perform competitively remarkable undetectability. Moreover, DeepKeyStego is the first to successfully design and implement symmetric (secret key) and asymmetric (public key) steganog- raphy, which considers the usage of keys to enhance security. Finally, we simulated our trained steganography in a practical situation and proved that the decoder can successfully recover 99.8% of embedded information, showing rather effectiveness and integrity.

[Download paper here](http://g3h4n.github.io/files/DeepKeyStego-HPCC2019.pdf)
