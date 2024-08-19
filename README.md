# Paper-List

### Research Papers List of Shaofeng Yin

I will try to summarize each paper in one or two sentence. The list will focus on RL.

Inspired by my friend Gao's  [Reading List](https://github.com/Winston-Gu/Paper-List).

# General
- arXiv 2018,06, A Tour of Reinforcement Learning: The View from Continuous Control. [Website](https://arxiv.org/abs/1806.09460). Just as the name suggests.

# Model-Based RL

# Offline RL

# Others

## Optimization

## Imitation Learning
- NeurIPS 2022, Behavior Transformers: Cloning $k$ modes with one stone. [Website](https://arxiv.org/pdf/2206.11251). Use Transformer to predict an action given previous obsversions, with the action represented as a k-means generated discrete token and a continueous offset.
- ICML2024, Behavior Generation with Latent Actions. [Website](https://arxiv.org/abs/2403.03181). Propose VQ-BeT, which just change the k-means above to residual VQ-VAE. Given the offset, tokens can be sparse and cheap, which enables robot deployment.
