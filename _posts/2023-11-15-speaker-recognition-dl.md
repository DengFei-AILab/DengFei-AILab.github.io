---
title: Multi-level attention network：Mixed time–frequency channel attention and multi-scale self-attentive standard deviation pooling for speaker recognition
description: >-
 Speaker Recognition.
author: dlh
date: 2023-11-15 20:00:00 +0800
categories: [语音识别, 说话人声纹识别]
tags: [Attention]
pin: false
---

## Abstract

In this paper, we propose a more efficient lightweight speaker recognition network, the multi-level attention network (MANet). MANet aims to generate more robust and discriminative speaker features by emphasizing features at different levels in the speaker recognition network through multi-level attention. The multi-level attention contains mixed time–frequency channel (MTFC) attention and multi-scale self-attentive standard deviation pooling (MSSDP). MTFC attention combines channel, time, and frequency information to capture global features and model long-term contexts. MSSDP can capture changes in frame-level features and aggregate frame-level features with different scales, generating a long-term, robust, and discriminative utterance-level feature. Therefore, MANet emphasizes the features of different levels. We performed extensive experiments on two popular datasets, Voxceleb and CN-Celeb. The proposed method is compared with the current state-of-the-art speaker recognition methods. It achieved EER/minDCF of 1.82%/0.1965, 1.94%/0.2059, 3.69%/0.3626, and 11.98%/0.4814 on the test sets Voxceleb1-O, Voxceleb1-E, Voxceleb1-H, and CN-Celeb, respectively. It is a more effective lightweight speaker recognition network, superior to most large speaker recognition networks and all lightweight speaker recognition networks tested, with an improved performance of 64% compared to the baseline system ThinResNet-34. Compared to the lightest EfficientTDNN-Small, it has only 0.6 million more parameters but 63% better performance. The performance of MANet is only 4% different compared to the state-of-the-art large model LE-Conformer. In the ablation experiments, our proposed attention method and aggregation model achieved the best experimental performance in Voxceleb1-O with EER/minDCF of 2.46%/0.2708, 2.39%/0.2417, respectively, which indicates that our proposed methods are a significant improvement over previous methods.

## Paper
[https://www.sciencedirect.com/science/article/abs/pii/S0952197623016238)

## Cite

### if this work is helpful for you, please cite
```
@article{deng2024multi,
  title={Multi-level attention network: Mixed time--frequency channel attention and multi-scale self-attentive standard deviation pooling for speaker recognition},
  author={Deng, Lihong and Deng, Fei and Zhou, Kepeng and Jiang, Peifan and Zhang, Gexiang and Yang, Qiang},
  journal={Engineering Applications of Artificial Intelligence},
  volume={128},
  pages={107439},
  year={2024},
  publisher={Elsevier}
}

```