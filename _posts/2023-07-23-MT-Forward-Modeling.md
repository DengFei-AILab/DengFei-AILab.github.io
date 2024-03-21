---
title: Magnetotelluric Deep Learning Forward Modeling and Its Application in Inversion
description: >-
 Magnetotelluric Deep Learning Forward Modeling and Its Application in Inversion
author: hj
date: 2023-07-23 20:00:00 +0800
categories: [信号处理, 正演建模]
tags: [Transformer]
pin: false

---

## Abstract

Magnetotelluric (MT) inversion and forward modeling are closely linked. The optimization and iteration processes of the inverse algorithm require frequent calls to forward modeling. However, traditional numerical simulations for forward modeling are computationally expensive; here, deep learning (DL) networks can simulate forward modeling and significantly improve forward speed. Applying DL for forward modeling in inversion problems requires a high-precision network capable of responding to fine changes in the model to achieve high accuracy in inversion optimization. Most existing MT studies have used a convolutional neural network, but this method is limited by the receptive field and cannot extract global feature information. In contrast, the Mix Transformer has the ability to globally model and extract features. In this study, we used a Mix Transformer to hierarchically extract feature information, adopted a multiscale approach to restore feature information to the decoder, and eliminated the skip connection between the encoder and decoder. We designed a forward modeling network model (MT-MitNet) oriented toward inversion. A sample dataset required for DL forward was established using the forward data generated from the traditional inverse calculation iteration process. The trained network quickly and accurately calculates the forward response. The experimental results indicate a high agreement between the forward results of MT-MitNet and those obtained with traditional methods. When MT-MitNet replaces the forward computation in traditional inversion, the inversion results obtained with it are also highly in agreement with the traditional inversion results. Importantly, under the premise of ensuring high accuracy, the forward speed of MT-MitNet is hundreds of times faster than that of traditional inversion methods in the same process.

## Paper
[Magnetotelluric Deep Learning Forward Modeling and Its Application in Inversion](https://www.mdpi.com/2072-4292/15/14/3667)

## Cite

### if this work is helpful for you, please cite
```
@article{deng2023magnetotelluric,
  title={Magnetotelluric deep learning forward modeling and its application in inversion},
  author={Deng, Fei and Hu, Jian and Wang, Xuben and Yu, Siling and Zhang, Bohao and Li, Shuai and Li, Xue},
  journal={Remote Sensing},
  volume={15},
  number={14},
  pages={3667},
  year={2023},
  publisher={MDPI}
}

```