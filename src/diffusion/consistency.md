# Consistency Models

Consistency Models are a type of generative model that offers faster sampling than traditional diffusion models while maintaining generation quality.

## Key Innovations

- Single-step generation: can generate high-quality samples in just one step
- Few-step generation: offers quality-speed trade-off with few sampling steps
- Distillation approach: distills knowledge from a pre-trained diffusion model

## Advantages

- Much faster sampling than regular diffusion models
- Deterministic sampling process
- Maintains generation quality comparable to diffusion models

## Technical Details

- Consistency functions: maps noise to data points
- Consistency distillation: training technique to learn consistency functions
- Self-conditioning: improves generation quality

## References

- [Song et al. (2023), "Consistency Models"](https://arxiv.org/abs/2303.01469)
