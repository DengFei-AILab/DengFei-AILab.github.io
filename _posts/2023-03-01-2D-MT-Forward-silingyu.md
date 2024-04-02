---
title: Accelerating magnetotelluric forward modeling with deep learning：Conv-BiLSTM and D-LinkNet
description: >-
 2-D MT Forward Moedling.
author: ysl
date: 2023-03-01 20:00:00 +0800
categories: [信号处理, 大地电磁正演建模]
tags: [CNN]
pin: false
---

## Abstract

Magnetotelluric forward modeling is important for exploring underground electromagnetic anomalies. Although directly solving the electromagnetic wave equation has high accuracy, its computational cost is usually unaffordable for large-scale models. A neural network (NN) can increase the computation of the magnetotelluric forward modeling; however, its numerical accuracy is limited owing to the use of a simple network structure and small-scale training data sets. We have increased the computational efficiency of the magnetotelluric forward modeling by deep learning based on cyclic NN and full convolution NN models. First, we have extracted the basic characteristics of the 2D-magnetotelluric forward modeling, which were important for selecting and optimizing the network. Then, we have developed two forward network models: convolutional bidirectional long short-term memory (Conv-BiLSTM) and LinkNet with pretrained encoder and dilated convolution (D-LinkNet). Next, we have constructed data sets of large-scale multiple anomalies. Finally, we have tested our models using various examples. Existing methods only consider a single anomaly and have low accuracy; in contrast, our methods can handle multianomaly models because they have strong generalization, even though the training is based on models with two or three anomalies. Numerical experiments find that the average accuracy of the Conv-BiLSTM and D-LinkNet forward network models was 87.5% and 95.3%, respectively. Compared with D-LinkNet, the Conv-BiLSTM network model has lower accuracy but higher computational efficiency. Our deep-learning schemes can significantly reduce the computational burdens of the magnetotelluric forward modeling, and thus allow us to perform swift inversions of multianomaly models.

## Paper
[https://library.seg.org/doi/abs/10.1190/geo2021-0667.1)

## Cite

### if this work is helpful for you, please cite
```
@article{deng2023accelerating,
  title={Accelerating magnetotelluric forward modeling with deep learning: Conv-BiLSTM and D-LinkNet},
  author={Deng, Fei and Yu, Siling and Wang, Xuben and Guo, Zhiheng},
  journal={Geophysics},
  volume={88},
  number={2},
  pages={E69--E77},
  year={2023},
  publisher={Society of Exploration Geophysicists}
}

```