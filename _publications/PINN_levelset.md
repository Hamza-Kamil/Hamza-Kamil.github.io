---
title: "Physics-informed neural networks for solving moving interface flow problems using the level set approach"
collection: publications
category: manuscripts
permalink: /publication/PINN_levelset
excerpt: 'Mathieu, Mullins, Kamil, Hamza, Fahsi, Adil, & Soulaïmani, Azzeddine'
date: 2025-10-09
venue: 'Physics of Fluids'
slidesurl: 'https://github.com/m-mullins/LS-PINN/'
paperurl: 'https://doi.org/10.1063/5.0289386'
citation: 'Mullins, M., Kamil, H., Fahsi, A., & Soulaimani, A. (2025). Physics-informed neural networks for solving moving interface flow problems using the level set approach. Physics of Fluids, 37, 107124.'
---

This paper advances the use of physics-informed neural networks (PINNs) architectures to address moving interface problems via the level set method. Originally developed for other partial differential equations-based problems, we particularly leverage physics-informed deep learning with residual adaptive networks' (PirateNet) features—including causal training, sequence-to-sequence learning, random weight factorization, and Fourier feature embeddings—and tailor them to handle problems with complex interface dynamics. Numerical experiments validate this framework on benchmark problems such as Zalesak's disk rotation and time-reversed vortex flow. We demonstrate that PINNs can efficiently solve level set problems exhibiting significant interface deformation without the need for upwind numerical stabilization, as generally required by classic discretization methods, or additional mass conservation schemes. However, incorporating an Eikonal regularization term in the loss function with an appropriate weight can further enhance results in specific scenarios. Our results indicate that PINNs with the PirateNet architecture surpass conventional PINNs in accuracy, achieving state-of-the-art error rates of L2=0.14% for Zalesak's disk and L2=0.85% for the time-reversed vortex flow problem, as compared to reference solutions. Additionally, for a complex two-phase flow dam break problem coupling the level set with the Navier–Stokes equations, we propose a geometric reinitialization method embedded within the sequence-to-sequence training scheme to ensure long-term stability and accurate inference of the level set field. The proposed framework has the potential to be broadly applicable to industrial problems that involve moving interfaces, such as free-surface flows in hydraulics and maritime engineering.
