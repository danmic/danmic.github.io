---
layout: post
title: "Speech Inpainting: Context-Based Speech Synthesis Guided by Video"
date: 2023-08-24
excerpt: "Montesinos J. F., Michelsanti D., Tan Z.-H., Jensen J."
tags: [speech, inpainting, audio-visual, transformer, multimodal, deep learning]
comments: false

---

### Authors

[Montesinos J. F.](https://juanmontesinos.com), **Michelsanti D.**, [Tan Z.-H.](http://kom.aau.dk/~zt/), [Jensen J.](http://kom.aau.dk/~jje/)

### Conference

Interspeech 2023

### Abstract

Audio and visual modalities are inherently connected in speech signals: lip movements and facial expressions are correlated with speech sounds. This motivates studies that incorporate the visual modality to enhance an acoustic speech signal or even restore missing audio information. Specifically, this paper focuses on the problem of audio-visual speech inpainting, which is the task of synthesizing the speech in a corrupted audio segment in a way that it is consistent with the corresponding visual content and the uncorrupted audio context. We present an audio-visual transformer-based deep learning model that leverages visual cues that provide information about the content of the corrupted audio. It outperforms the previous state-of-the-art audio-visual model and audio-only baselines. We also show how visual features extracted with AV-HuBERT, a large audio-visual transformer for speech recognition, are suitable for synthesizing speech.

[Full text](https://arxiv.org/abs/2306.00489) [Slides](slides_interspeech2023.pdf) [Demo](https://ipcv.github.io/avsi/)  