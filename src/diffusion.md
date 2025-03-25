# 扩散模型

扩散模型是一类已经彻底改变了基于AI的内容创作的生成模型。这些模型通过逐渐向数据添加噪声，然后学习逆转这一过程来生成新样本。

## 概述

扩散模型已成为生成式AI中最强大的方法之一，特别是对于图像，但也越来越多地应用于音频、视频和3D内容等其他模态。它们的工作原理是：

1. 前向过程：逐渐向数据添加噪声，直到变成纯噪声
2. 反向过程：学习迭代去噪以生成新数据

## 主要优势

- 高质量生成
- 灵活的条件机制
- 与GANs相比训练更稳定
- 强大的理论基础

## 扩散模型的类型

本节介绍扩散模型的几个重要变体：

- [VAE](./diffusion/vae.md)：变分自编码器的相关优化
- [DDPM](./diffusion/ddpm.md)：原始的去噪扩散概率模型
- [Score-based Diffusion](./diffusion/one-or-two-stage.md)：单阶段or两阶段扩散模型
- [Stable Diffusion](./diffusion/stable-diffusion.md)：用于文本到图像生成的潜在扩散模型
- [一致性模型](./diffusion/consistency.md)：快速采样扩散变体
- [Vector Quantized Diffusion](./diffusion/vector-quantized-diffusion.md)：向量量化扩散模型



每个子章节都提供了关于模型架构、训练过程和应用的详细解释。
