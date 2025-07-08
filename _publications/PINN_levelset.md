---
title: "Physics-informed neural networks for solving moving interface flow problems using the level set approach"
collection: publications
category: manuscripts
permalink: /publication/PINN_levelset
excerpt: 'Mathieu, Mullins, Kamil, Hamza, Fahsi, Adil, & Soulaïmani, Azzeddine'
date: 2025-07-04
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2502.02440'
citation: 'Mullins, M., Kamil, H., Fahsi, A., & Soulaimani, A. (2025). Physics-informed neural networks for solving moving interface flow problems using the level set approach. arXiv preprint arXiv:2502.02440'
---

This paper advances the use of physics-informed neural networks (PINNs) architectures to address
moving interface problems via the level set method. Originally developed for other PDE-based
problems, we particularly leverage PirateNet’s features—including causal training, sequence-tosequence
learning, random weight factorization, and Fourier feature embeddings—and tailor them
to achieve superior performance in modeling interface dynamics. Numerical experiments validate
this framework on benchmark problems such as Zalesak’s disk rotation and time-reversed vortex
flow. We demonstrate that PINNs can efficiently solve level set problems exhibiting significant interface
deformation without the need for upwind numerical stabilization, as generally required by
classic discretization methods, or the need for mass conservation schemes. However, incorporating
an Eikonal regularization term in the loss function with an appropriate weight can further enhance
results in specific scenarios. Our results indicate that PINNs with the PirateNet architecture
surpass conventional PINNs in accuracy, achieving state-of-the-art error rates of L2 = 0.14% for
Zalesak’s disk and L2 = 0.85% for the time-reversed vortex flow problem, as compared to reference
solutions. Additionally, for a complex two-phase flow dam break problem which couples the level
set with the Navier-Stokes equations, we propose a geometric reinitialization method embedded in
the sequence-to-sequence training scheme that allows long term inference of the level set field.