# Diffusion Model

Diffusion models are a class of generative models that have revolutionized AI-based content creation. These models work by gradually adding noise to data and then learning to reverse this process to generate new samples.

## Overview

Diffusion models have emerged as one of the most powerful approaches for generative AI, particularly for images, but increasingly for other modalities like audio, video, and 3D content. They work by:

1. Forward process: Gradually adding noise to data until it becomes pure noise
2. Reverse process: Learning to iteratively denoise to generate new data

## Key Advantages

- High-quality generation
- Flexible conditioning mechanisms
- Stable training compared to GANs
- Strong theoretical foundation

## Types of Diffusion Models

This section covers several important variants of diffusion models:

- [DDPM](./diffusion/ddpm.md): The original denoising diffusion probabilistic models
- [Stable Diffusion](./diffusion/stable-diffusion.md): Latent diffusion models for text-to-image generation
- [Consistency Models](./diffusion/consistency.md): Fast sampling diffusion variants

Each sub-chapter provides detailed explanations of the model architecture, training process, and applications.
