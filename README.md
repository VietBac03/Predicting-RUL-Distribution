# Predicting-RUL-Distribution
This is the source code for paper "Adaptive Sensory Updates and Disturbance Compensation for Predicting RUL Distribution in Nonlinear Degradation Systems"

The code implements a probabilistic Remaining Useful Life (RUL) prediction framework that integrates:

* Hybrid Basis Function Identification (HBFI) for nonlinear degradation modeling
* Sparse Bayesian Learning (SBL) for automatic basis selection
* Disturbance Observer (DO) for compensating low-frequency disturbances
* Adaptive Power-Law (APL) Bayesian update for robust online parameter updating

The proposed method enables robust probabilistic RUL prediction under noisy and time-varying operating conditions.

**Datasets**

The repository includes three types of datasets used in the paper:

**1. Simulation dataset**

Synthetic degradation data generated using a nonlinear degradation model.

The simulation setup follows the mathematical formulation described in the manuscript.

**2. Lithium-ion Battery (LiB) dataset**

Battery capacity degradation data used to evaluate the performance of the proposed RUL prediction framework.

Health indicator:

Normalized capacity degradation

Failure threshold:

Capacity reaching the defined end-of-life threshold.

Datasets

The repository includes three types of datasets used in the paper:

**1. Simulation dataset**

**2. Lithium-ion Battery (LiB) dataset**

**3. IGBT dataset**


**Requirements**

The code was developed using:

MATLAB R2022b or later

Required toolboxes:

Statistics and Machine Learning Toolbox

Signal Processing Toolbox
