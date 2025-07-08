---
title: "Deep neural operators for inversion and surrogate modeling in unsaturated flow"
collection: talks
type: "Talk"
permalink: /talks/DigitalTwins_conf_paris_inversion
excerpt: 'Kamil, Hamza, Soulaïmani, Azzeddine, & Beljadid, Abdelaziz'
venue: "3rd Digital Twins in Engineering Conference & AICOMAS"
date: 2025-02-20
location: "Benguerir, Morocco"
paperurl: 'https://www.researchgate.net/publication/390201327_Deep_neural_operators_for_inversion_and_surrogate_modeling_in_unsaturated_flows'
citation: 'Kamil, H., Soulaïmani, A., & Beljadid, A. (2025). Deep neural operators for inversion and surrogate modeling in unsaturated flow. 3rd Digital Twins in Engineering Conference (DTE 2025) & AICOMAS 2025, Paris, France, 17–21 February.'
---

**Presentation slides:** [Download](/files/DTE_2025___1st_ECCOMAS_paris.pdf)


Accurate modeling of water infiltration in unsaturated soils is essential for a variety of applications, including irrigation management, groundwater recharge estimation, and contaminant transport prediction. This modeling relies on mathematical models that require the calibration of numerous unknown soil parameters based on field or laboratory data. However, the calibration process is challenging due to the complexity of the inverse problem and the high uncertainty in the available data. Traditional methods that combine optimization tools with high-fidelity numerical solvers often result in time-consuming processes, particularly for large-scale, long-term simulations or when multiple parameters need to be calibrated simultaneously. In this study, we propose a deep learning approach using Neural Operators to efficiently address the inverse modeling problem for water flow in unsaturated soils. Specifically, we utilize the DeepONet model [1] to learn the relationship between soil parameters and the resulting water content profiles over time and space. Once trained, the DeepONet serves as a surrogate model, which we couple with an optimization algorithm to predict the soil parameters for a given scenario. To further enhance the calibration process, we employ various optimization strategies, including a sequential approach where a genetic-like algorithm provides initial estimates that are refined using gradient-based methods. We validate the proposed methodology through numerical experiments. The results demonstrate that our coupled surrogate-optimization approach outperforms both Physics-Informed Neural Networks (PINNs) [2] and traditional neural network methods for inverse modeling of unsaturated flow.

REFERENCES 

[1] Lu, L., Jin, P., & Karniadakis, G. E. (2019). Deeponet: Learning nonlinear operators for identifying differential equations based on the universal approximation theorem of operators. arXiv preprint arXiv:1910.03193. 

[2] Kamil, H., Soulaïmani, A., & Beljadid, A. (2024). A transfer learning physics-informed deep learning framework for modeling multiple solute dynamics in unsaturated soils. Computer Methods in Applied Mechanics and Engineering, 431, 117276.
  