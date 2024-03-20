---
title: Application of Split Residual Multilevel Attention Network in Speaker Recognition
description: >-
 Speaker recognition based on Split-ResNet and Dual Time-Frequency Attention(DTFA).
author: GG
date: 2023-08-29 20:00:00 +0800
categories: [语音识别, 说话人声纹识别]
tags: [ResNet]
pin: false
# img_path: '/posts/20180809'
---

## Abstract

Current speaker recognition systems are mainly for the combined application of network architectures and attention mechanisms, however, lightweight networks are not able to extract frame-level features of speaker speech well, and deeper and wider networks also face the problems of slower inference and excessive number of parameters. To this end, we proposes Split-ResNet, a network structure for split residuals, which can obtain a combination of multiple receptive field at a finer-grained level, thus obtaining a variety of feature representations with different scale combinations and producing more informative and comprehensive multi-scale features. In addition we propose a dual time-frequency attention (DTFA) that enhances key features and suppresses unimportant features by focusing on features in the time and frequency domains and learning weights from the time and frequency channels, respectively. We finally tested the speaker recognition system using a combination of Split-ResNet and DTFA against other speaker recognition systems on the Voxceleb1-O test set. The test results show that the speaker recognition system proposed in this paper is 0.98%, 0.39%, 0.69% and 0.47% lower in EER compared with SpeechNAS, RawNet2, Y-vector and CNN+Transformer, respectively, proving that DTFA+Split-ResNet is a speaker recognition system with good speaker audio feature extraction capability and discriminative capability.

## Paper
[Application of Split Residual Multilevel Attention Network in Speaker Recognition.](https://ieeexplore.ieee.org/document/10223220)


## Cite

### if this work is helpful for you, please cite
```
@ARTICLE{10223220,
  author={Wang, Jiji and Deng, Fei and Deng, Lihong and Gao, Ping and Huang, Yuanxiang},
  journal={IEEE Access}, 
  title={Application of Split Residual Multilevel Attention Network in Speaker Recognition}, 
  year={2023},
  volume={11},
  number={},
  pages={89359-89368},
  keywords={Feature extraction;Speaker recognition;Data mining;Time-frequency analysis;Task analysis;Mathematical models;Attention mechanisms;DTFA;speaker identification;split-ResNet},
  doi={10.1109/ACCESS.2023.3306026}}

```