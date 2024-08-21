# Paper-List

### Research Papers List of Shaofeng Yin

I will try to summarize each paper in one or two sentence. The list will focus on RL.

Inspired by my friend Gao's  [Reading List](https://github.com/Winston-Gu/Paper-List).

## General
- arXiv 2018,06, A Tour of Reinforcement Learning: The View from Continuous Control. [Website](https://arxiv.org/abs/1806.09460). Just as the name suggests.

## Model-Based RL
### Model for Fake Data Generation
- NeurIPS 2019, When to Trust Your Model: Model-Based Policy Optimization. [Website](https://arxiv.org/abs/1906.08253). Model-Based acceleration for Model-Free RL with the help of probabilistic network genreated shot horizon rollouts.
### Model for Planning
- ICML 2022, Planning with Diffusion for Flexible Behavior Synthesis. [Website](https://arxiv.org/abs/2205.09991). Use diffusion model to first predict and planning simultaneously.
- NeurIPS 2018, Deep Reinforcement Learning in a Handful of Trials using Probabilistic Dynamics Models. [Website](https://arxiv.org/abs/1805.12114). Inherent stochasticities or subjective uncertainty? Why not both? Inequality:  PE > P > DE > D. "E" for "ensemble", "D" for deterministic network and "P" for "probobility" network.
### Real World RL
- ICLR 2024, ASID: ACTIVE EXPLORATION FOR SYSTEM IDENTIFICATION IN ROBOTIC MANIPULATION. [Website](https://arxiv.org/pdf/2404.12308). Trajectories sensitive to the unknown parameters (induced by maximizing Fisher Information Maximization) are good candidates for system identification.

## Offline RL

## Others

### Optimization

### Imitation Learning
- NeurIPS 2022, Behavior Transformers: Cloning $k$ modes with one stone. [Website](https://arxiv.org/pdf/2206.11251). Use Transformer to predict an action given previous obsversions, with the action represented as a k-means generated discrete token and a continueous offset.
- ICML 2024, Behavior Generation with Latent Actions. [Website](https://arxiv.org/abs/2403.03181). Propose VQ-BeT, which just change the k-means above to residual VQ-VAE. Given the offset, tokens can be sparse and cheap, which enables robot deployment. 
- AISTATS 2011, A Reduction of Imitation Learning and Structured Prediction to No-Regret Online Learning. [Website](https://arxiv.org/pdf/1011.0686). Always aggregate your datasets with updated policies and keep an eye on the expert at the same time.

