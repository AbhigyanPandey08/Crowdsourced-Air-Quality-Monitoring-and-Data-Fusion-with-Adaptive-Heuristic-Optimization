# -Crowdsourced-Air-Quality-Monitoring-and-Data-Fusion-with-Intelligent-Heuristic-Optimization
Below is a clean, publication-grade GitHub README, written in the same style, tone, and structure as your sample, but fully aligned with your crowdsourced AQI data-fusion paper and suitable for EMS / Zenodo / reviewers.

You can paste this directly into README.md.

Crowdsourced-Air-Quality-Monitoring-and-Data-Fusion-with-Adaptive-Heuristic-Optimization

Adaptive Data-Fusion and Heuristic Optimization for Reliable Air-Quality Monitoring from Crowdsourced Sensors

This repository accompanies the research work developing an intelligent hybrid data-fusion framework for robust Air Quality Index (AQI) estimation under sensor heterogeneity, uncertainty, and missing data conditions.

Authors

Abhigyan Pandey¹, Arghya Chakraborty¹, Aditya Narayan¹, Maana Ajmera¹, Abhipsa Nayak¹

Institutions

¹Department of Computer Science and Engineering, Rajiv Gandhi Institute of Petroleum Technology, Jais, Amethi, India

Year: 2026

**Overview**

This repository contains the complete data processing, fusion algorithms, heuristic optimization routines, and evaluation workflows developed for the study:
“Reliable air quality estimation from heterogeneous crowdsourced data using an adaptive hybrid data-fusion framework”
The work addresses limitations of conventional AQI estimation by introducing a layered fusion architecture that integrates statistical filtering, regression-based trust modeling, and adaptive heuristic optimization to infer bias-corrected and temporally stable AQI estimates from heterogeneous, crowdsourced pollutant observations.

**Research Highlights:**
**Methodological Contributions**

Hybrid Fusion Architecture: Integration of Weighted Regression (WR), Kalman Smoothing (KS), and Kalman Filtering (KF)

Adaptive Trust Learning: Sensor reliability inferred through variance-based (σ²) convergence dynamics

Heuristic Optimization: Comparative implementation of

Genetic Algorithm–Particle Swarm Optimization (GA–PSO)

NSGA-II (accuracy–sparsity trade-off)

Simulated Annealing (robust local refinement)

**Key Findings**

Mean AQI RMSE reduced by ~40% compared to baseline fusion

GA–PSO achieved best performance in ~63% of evaluated cities

Framework operates without explicit sensor calibration metadata

Stable generalization demonstrated across 68 Indian cities (2015–2024)

**Practical Relevance**

Enables cost-effective urban air-quality monitoring

Supports explainable decision-making for environmental management

Scalable to IoT-based environmental sensing systems

Dataset Description

Coverage: 68 Indian cities

Period: 2015–2024

Variables: PM₂.₅, PM₁₀, NO₂, SO₂, CO, O₃, AQI

Records: 36,802 observations

Dataset archived on Zenodo: Pandey, A., Chakraborty, A., Narayan, A., Ajmera, M., & Nayak, A. (2026). Air Quality Index and Pollutant Dataset for 68 Indian Cities (2015-2024) (Version v3) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.18633863

**Methodology Workflow**

1. Crowdsourced Data Acquisition & Cleaning

2. AQI Gap Filling via Kalman Smoothing

3. Weighted Regression-Based Spatial Fusion

4. Temporal Stabilization using Kalman Filtering

5. Adaptive Trust Optimization

6. Genetic Algorithm–Particle Swarm Optimization (GA–PSO) 

7. NSGA-II (multi-objective optimization)

8. Simulated Annealing (robust refinement)

Cross-City & Temporal Robustness Evaluation

Explainability via Trust Weight Evolution
