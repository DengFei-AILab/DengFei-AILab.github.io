---
title: ResSKNet-SSDP 
description: >-
Effective and Light End-To-End Architecture for Speaker Recognition.
author: dlh
date: 2023-01-20 20:00:00 +0800
categories: [语音识别, 说话人声纹识别]
tags: [ResNet]
pin: false
---

## Abstract

In speaker recognition tasks, convolutional neural network (CNN)-based approaches have shown significant success. Modeling the long-term contexts and efficiently aggregating the information are two challenges in speaker recognition, and they have a critical impact on system performance. Previous research has addressed these issues by introducing deeper, wider, and more complex network architectures and aggregation methods. However, it is difficult to significantly improve the performance with these approaches because they also have trouble fully utilizing global information, channel information, and time-frequency information. To address the above issues, we propose a lighter and more efficient CNN-based end-to-end speaker recognition architecture, ResSKNet-SSDP. ResSKNet-SSDP consists of a residual selective kernel network (ResSKNet) and self-attentive standard deviation pooling (SSDP). ResSKNet can capture long-term contexts, neighboring information, and global information, thus extracting a more informative frame-level. SSDP can capture short- and long-term changes in frame-level features, aggregating the variable-length frame-level features into fixed-length, more distinctive utterance-level features. Extensive comparison experiments were performed on two popular public speaker recognition datasets, Voxceleb and CN-Celeb, with current state-of-the-art speaker recognition systems and achieved the lowest EER/DCF of 2.33%/0.2298, 2.44%/0.2559, 4.10%/0.3502, and 12.28%/0.5051. Compared with the lightest x-vector, our designed ResSKNet-SSDP has 3.1 M fewer parameters and 31.6 ms less inference time, but 35.1% better performance. The results show that ResSKNet-SSDP significantly outperforms the current state-of-the-art speaker recognition architectures on all test sets and is an end-to-end architecture with fewer parameters and higher efficiency for applications in realistic situations. The ablation experiments further show that our proposed approaches also provide significant improvements over previous methods.

## Paper
[https://www.mdpi.com/1424-8220/23/3/1203)

## Cite

### if this work is helpful for you, please cite
```
@article{deng2023ressknet,
  title={ResSKNet-SSDP: Effective and Light End-To-End Architecture for Speaker Recognition},
  author={Deng, Fei and Deng, Lihong and Jiang, Peifan and Zhang, Gexiang and Yang, Qiang},
  journal={Sensors},
  volume={23},
  number={3},
  pages={1203},
  year={2023},
  publisher={MDPI}
}

```