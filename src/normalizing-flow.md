# Normalizing Flow

Normalizing Flows are a family of generative models that use invertible transformations to map between a simple base distribution and a complex target distribution.

## Key Concepts

- **Invertible Transformations**: Bijective mappings between spaces
- **Change of Variables Formula**: Mathematical foundation that allows exact likelihood computation
- **Flow-based Generation**: Sampling from a simple distribution and transforming through learned flows

## Types of Normalizing Flows

- **NICE/RealNVP**: Coupling layers with affine transformations
- **Glow**: Extended RealNVP with 1x1 convolutions
- **Autoregressive Flows (IAF, MAF)**: Using autoregressive transformations
- **Continuous Normalizing Flows**: Defining flows using ordinary differential equations

## Advantages

- **Exact Likelihood**: Unlike VAEs, flows provide exact likelihood computation
- **Efficient Sampling**: Unlike autoregressive models, sampling can be parallelized
- **Invertibility**: Can transform in both directions (generation and inference)
- **Stable Training**: More stable than GANs, using maximum likelihood

## Applications

- **Image Generation**: High-quality image synthesis
- **Anomaly Detection**: Identifying outliers in data
- **Density Estimation**: Learning complex probability distributions
- **Variational Inference**: More expressive posterior approximations

## Challenges

- **Architectural Constraints**: Requiring invertibility limits model expressiveness
- **Computational Cost**: Some flows can be computationally expensive
- **High-dimensional Data**: Scaling to very high dimensions can be challenging

## References

- [Rezende & Mohamed (2015), "Variational Inference with Normalizing Flows"](https://arxiv.org/abs/1505.05770)
- [Dinh et al. (2016), "Density estimation using Real NVP"](https://arxiv.org/abs/1605.08803)
- [Kingma & Dhariwal (2018), "Glow: Generative Flow with Invertible 1x1 Convolutions"](https://arxiv.org/abs/1807.03039)
