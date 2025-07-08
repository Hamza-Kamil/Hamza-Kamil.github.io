---
title: "Physics-informed neural operators for efficient modeling of infiltration in porous media"
collection: publications
category: manuscripts
permalink: /publication/DeepONet_JCP
excerpt: 'Kamil, Hamza, Soulaïmani, Azzeddine, & Beljadid, Abdelaziz'
date: 2025-06-08
venue: 'Journal of Computational Physics, 114156'
slidesurl: 'https://github.com/Hamza-Kamil/DeepONet-WaterFlow-Soils'
paperurl: 'https://www.sciencedirect.com/science/article/pii/S0021999125004395'
citation: 'Kamil, H., Soula, A., & Beljadid, A. (2025). Physics-informed neural operators for efficient modeling of infiltration in porous media. Journal of Computational Physics, 114156.'
---

The development of efficient irrigation systems relies on accurately solving the water flow model described by the highly nonlinear Richards equation. Many forward simulations are required to evaluate various settings, such as irrigation duration, emitter flux rate, initial soil moisture distribution, and the type of irrigation system employed. This often leads to slow and cumbersome decision-making processes. In this study, we propose an efficient and accurate deep learning solver for modeling water flow in unsaturated soils. The model is a physics-informed deep operator network (DeepONet) with an improved architecture designed to accurately solve the highly nonlinear Richards equation. The aim is to train the DeepONet model to learn the mapping between different initial soil moisture conditions and emitter fluxes to the corresponding water content profile in the time-space domain. By incorporating physical constraints, we reduce the need for large amounts of labeled data while maintaining accuracy. Once trained, the DeepONet model provides soil moisture predictions within fractions of a second at any desired time or space location and with any desired resolution, given any initial conditions and fluxes. The reliability of the DeepONet model is evaluated through numerical experiments on two-dimensional soil geometries with different soil types. The results highlight the efficiency of DeepONet predictions, as they closely match reference solutions. Additionally, the model’s extrapolation capability was evaluated, showing that fine-tuning with physical constraints or available soil moisture data improved its prediction accuracy. This study represents a step towards developing an efficient and rapid physics-informed surrogate model for quick decision-making in irrigation strategies.
