---
title: "A comparative study of physics-informed neural network strategies for modeling water and nitrogen transport in unsaturated soils"
collection: publications
category: manuscripts
permalink: /publication/PINN-MPINN-hydrology
excerpt: 'Kamil, Hamza, Soulaïmani, Azzeddine, & Beljadid, Abdelaziz'
date: 2025-06-16
venue: 'Journal of Hydrology, 133624'
slidesurl: 'https://github.com/Hamza-Kamil/PINN-MPINN-Water-Solute'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S002216942500962X'
citation: 'Kamil, H., Soulaïmani, A., & Beljadid, A. (2025). A comparative study of physics-informed neural network strategies for modeling water and nitrogen transport in unsaturated soils. Journal of Hydrology, 133624.'
---

A deep understanding of subsurface flow dynamics—including water infiltration and the transport of single or multiple solutes in unsaturated soils—is critical for a wide range of engineering applications. Traditionally, these complex processes have been modeled using standard numerical solvers, which remain conventional in many studies. However, a recent and promising methodology gaining traction is physics-informed neural networks (PINNs). This approach is based on training neural networks to solve partial differential equations by combining available data with the physical principles embedded in the equations. In this study, we analyze several PINN solvers to tackle the coupled model of water flow and single or multispecies solute transport in unsaturated soils. This model is governed by the highly nonlinear Richards equation and advection–dispersion equations. To improve the training of the solvers, we integrate several strategies aimed at capturing the system’s full complexity.
The numerical experiments cover one- and two-dimensional scenarios, tackling forward and inverse problems. The results obtained from PINN are compared with reference solutions and experimental data sourced from existing literature. Our analysis underscores the effectiveness of employing sequential training alongside an adaptive activation technique for modeling the coupled water–solute system. This methodology not only improves accuracy and training efficiency but also enables an accurate estimation of the unknown ammonium nitrification rate from sparse measurements.
