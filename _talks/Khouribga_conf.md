---
title: "Efficient modeling of unsaturated flow in soils using physics-informed deep neural operators"
collection: talks
type: "Talk"
permalink: /talks/Khouribga_conf
excerpt: 'Kamil, Hamza, Soulaïmani, Azzeddine, & Beljadid, Abdelaziz'
venue: "International Conference on Computer Engineering and Artificial Intelligence, I2CEAI"
date: 2024-09-28
location: "Khouribga, Morocco"
citation: 'Kamil, H., Soulaïmani, A., & Beljadid, A. (2024). Efficient modeling of unsaturated flow in soils using physics-informed deep neural operators. First International Conference on Computer Engineering and Artificial Intelligence I2CEAI 2024, Khouribga, Morocco, 27–28 September.'
---

The design and optimization of efficient irrigation systems rely on accurately modeling water flow in unsaturated soils, which is governed by the highly nonlinear Richards equation. Solving this equation under different scenarios, such as varying irrigation durations, emitter flux rates, and soil moisture distributions, is computationally intensive and time-consuming. This slows down decision-making processes, especially when rapid adjustments are needed in real-world agricultural settings.

In this study, we propose a deep learning-based approach using Physics-Informed Neural Operators to efficiently model water flow. Specifically, we employ a Deep Operator Network (DeepONet) tailored to solve the Richards equation. The model learns the mapping between initial soil moisture conditions and emitter fluxes to water content profiles in both time and space, enabling flexible and high-resolution predictions. By incorporating physical constraints, we reduce the need for large amounts of labeled data while maintaining accuracy. Once trained, the model provides near-instantaneous predictions of soil moisture dynamics across any spatial resolution or time interval.

We validate the model through numerical experiments on two-dimensional soil geometries with three distinct soil textures. The results demonstrate its ability to replicate reference solutions efficiently, making it ideal for applications requiring fast computations. Furthermore, the model’s extrapolation capability improves when supplemented with physical constraints or sparse data, enhancing prediction accuracy.

This work advances the development of fast, reliable surrogate models for optimizing irrigation strategies. By significantly reducing computational demands, our approach supports real-time decision-making in precision agriculture, promoting more sustainable and efficient irrigation practices.