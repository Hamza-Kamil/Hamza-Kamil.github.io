---
title: "A transfer learning physics-informed deep learning framework for modeling multiple solute dynamics in unsaturated soils."
collection: publications
category: manuscripts
permalink: /publication/TLPINN-paper-cmame
excerpt: 'Kamil, Hamza, Soulaïmani, Azzeddine, & Beljadid, Abdelaziz'
date: 2024-8-14
venue: 'Computer Methods in Applied Mechanics and Engineering, 431, 117276'
slidesurl: 'https://github.com/Hamza-Kamil/Transfer-Learning-PINN-Nitrogen'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0045782524005322'
citation: 'Kamil, H., Soulaïmani, A., & Beljadid, A. (2024). A transfer learning physics-informed deep learning framework for modeling multiple solute dynamics in unsaturated soils. Computer Methods in Applied Mechanics and Engineering, 431, 117276.'
---

Modeling subsurface flow and transport phenomena is essential for addressing a wide range of challenges in engineering, hydrology, and ecology. The Richards equation is a cornerstone for simulating infiltration, and when coupled with advection–dispersion equations, it provides insights into solute transport. However, the complexity of this coupled model increases significantly when dealing with multiple solute transport. Physics-informed neural networks (PINNs) offer a flexible technique that merges data-driven approaches with the underlying physics principles, enabling the direct incorporation of physical laws or constraints into the neural network training process. Nevertheless, employing PINNs for solving multi-physics problems can present challenges during training, particularly in achieving convergence to realistic concentration profiles. Our study introduces a transfer learning technique to tackle the challenge of modeling multiple species transport in unsaturated soils. This approach aims to improve the accuracy of the PINN framework by decoupling the training process and solving the governing partial differential equations (PDEs) sequentially. We incorporate various strategies to optimize and accelerate the training process. Specifically, we begin by solving the Richards equation and then transfer the acquired knowledge to subsequent solute PINN solvers. This strategy leverages the fact that these PDEs have some similarities in their structure as advection–diffusion equations. To rigorously validate our approach, we conduct 1D numerical experiments and extend our analysis to encompass 2D problems, and inverse problems for homogeneous soils, as well as numerical tests using layered soils. Our findings indicate that transferring learned features is more advantageous than utilizing random features, highlighting the effectiveness of the proposed strategy.



