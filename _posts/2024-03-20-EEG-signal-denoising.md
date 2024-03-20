---
title: EEGDiR
description: >-
 Electroencephalogram denoising network for temporal information storage and global modeling through Retentive.
author: wangbin
date: 2024-03-20 00:00:00 +0800
categories: [信号处理, 脑电波去噪]
tags: [Rententive Network]
pin: false
# img_path: '/posts/20180809'
---

## Abstract

Electroencephalogram (EEG) signals play a pivotal role in clinical medicine, brain research, and neurological disease studies. However, susceptibility to various physiological and environmental artifacts introduces noise in recorded EEG data, impeding accurate analysis of underlying brain activity. Denoising techniques are crucial to mitigate this challenge. Recent advancements in deep learningbased approaches exhibit substantial potential for enhancing the signal-to-noise ratio of EEG data compared to traditional methods. In the realm of large-scale language models (LLMs), the Retentive Network (Retnet) infrastructure, prevalent for some models, demonstrates robust feature extraction and global modeling capabilities. Recognizing the temporal similarities between EEG signals and natural language, we introduce the Retnet from natural language processing to EEG denoising. This integration presents a novel approach to EEG denoising, opening avenues for a profound understanding of brain activities and accurate diagnosis of neurological diseases. Nonetheless, direct application of Retnet to EEG denoising is unfeasible due to the one-dimensional nature of EEG signals, while natural language processing deals with two-dimensional data. To facilitate Retnet application to EEG denoising, we propose the signal embedding method, transforming one-dimensional EEG signals into two dimensions for use as network inputs. Experimental results validate the substantial improvement in denoising effectiveness achieved by the proposed method.

## Paper
[EEGDiR: Electroencephalogram denoising network for temporal information storage and global modeling through Retentive Network]( )

## network 
![网络结构图](../assets/img/wangbin/eeg.jpg)
## Code

### The code implementation is [here.](https://github.com/woldier/EEGDiR)

## Cite

### if this work is helpful for you, please cite
```

```

