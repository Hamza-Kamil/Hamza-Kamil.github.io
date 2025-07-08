---
title: "Semi-implicit schemes for modeling water flow and solute transport in unsaturated soils"
collection: publications
category: manuscripts
permalink: /publication/IMEX_ADWR
excerpt: 'Kamil, Hamza, Soulaïmani, Azzeddine, & Beljadid, Abdelaziz'
date: 2024-10-11
venue: 'Advances in Water Resources, 193, 104835'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0309170824002227'
citation: 'Kamil, H., Beljadid, A., Soulaïmani, A., & Bourgault, Y. (2024). Semi-implicit schemes for modeling water flow and solute transport in unsaturated soils. Advances in Water Resources, 193, 104835.'
---

The coupled model of water flow and solute transport in unsaturated soils is addressed in this study. Building upon previous research findings by Keita, Beljadid, and Bourgault, we investigate a class of second-order time-stepping techniques where two free parameters are introduced, to identify the most stable and accurate scheme. The spatial discretization of the Richards equation is accomplished using the mixed finite element method. The proposed approach involves formulating noniterative schemes using an extrapolation formula and Taylor approximation in time to linearize nonlinear terms. Additionally, a specialized regularization technique is applied to ensure the convergence of the proposed numerical methods. Numerical simulations are conducted to determine the optimal scheme for solving the Richards equation, which is subsequently extended to the transport equation.

Numerical simulations of water flow reveal the good accuracy of three schemes—SBDF, MSBDF, and Richards-M2 for homogeneous and heterogeneous soils. Notably, the SBDF scheme stands out for its computational efficiency and stability, especially when gravity forces dominate over capillary forces. Through numerical analysis of the coupled semi-implicit schemes, our results affirm the SBDF scheme’s superior robustness, establishing it as the optimal choice among the proposed numerical methods. Therefore, the SBDF scheme is employed to solve the coupled model of water flow and solute transport. We conducted various numerical experiments to solve the coupled model, addressing scenarios including single and multispecies nitrogen transport, pore water electrical conductivity, and nitrate transport. The SBDF scheme’s accuracy was rigorously verified through comparisons with reference solutions and experimental data. This establishes the SBDF scheme as an efficient alternative to traditional implicit methods for modeling water flow and solute transport in unsaturated soils.