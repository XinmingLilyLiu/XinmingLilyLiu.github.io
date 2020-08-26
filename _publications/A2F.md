---
title: "Analog-to-Feature (A2F) Conversion for Audio-Event Classification"
collection: publications
permalink: /publication/A2F
excerpt: 'In this paper, we propose a novel and optimized classification algorithm called analog-to-feature (A2F) conversion. It provides a more energy-efficient solution to always-on sensors for audio-event classification.'
date: 2018-05-18
venue: '26th European Signal Processing Conference (EUSIPCO)'
prof: "Christoph Studer"
profurl: "https://www.ece.cornell.edu/faculty-directory/christoph-studer"
---
Always-on sensors continuously monitor the environment for certain events. Such sensors are often integrated on battery-powered devices, e.g., home automation devices or virtual assistants, which require power-efficient classification pipelines. However, conventional classification pipelines that digitize the analog signals at Nyquist rate followed by digital feature extraction and classification are wasteful in a sense that the “feature rate” is generally much smaller than the Nyquist rate. In this paper, we propose a novel classification pipeline called analog-to-feature (A2F) conversion that directly acquires features in the analog domain using non-uniform wavelet sampling (NUWS). Our approach effectively combines Nyquist-rate sampling and digital feature extraction, which has the potential to significantly reduce the power and costs of signal classification. We demonstrate the efficacy of our approach for the detection of audio events and show that NUWS-based A2F conversion is able to outperform existing methods that use compressive sensing.

[Download paper here](http://xinminglilyliu.github.io/files/A2F.pdf)
