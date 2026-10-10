# Wastewater Ammonium Model Calibration

## Overview

This project focuses on modelling ammonium (NH₄⁺) dynamics in sewer systems and wastewater treatment plant inlets.

The modelling workflow combines data analysis, model selection, sensitivity analysis, parameter estimation, calibration, and validation to evaluate how well the model reproduces observed NH₄⁺ behaviour under dry- and wet-weather conditions.

## Project Objectives

- Analyse temporal patterns in wastewater flow and NH₄⁺ dynamics
- Compare alternative model structures
- Identify influential model parameters using sensitivity analysis
- Select an appropriate optimization method for parameter estimation
- Calibrate sensitive model parameters against observed data
- Evaluate calibration performance and parameter bounds
- Assess model performance under different weather conditions

## Modelling Approach

The project followed a structured environmental modelling workflow:

1. Data preprocessing and exploratory analysis
2. Model diagnosis and selection
3. Local sensitivity analysis
4. Global sensitivity analysis using the Morris method
5. Selection of parameters for calibration
6. Global optimization using dual annealing
7. Calibration and validation
8. Evaluation of model performance and limitations

## Key Findings

Sensitivity analysis identified α₀ as the dominant model parameter, with λ₂ also influencing model behaviour.

Based on these results, α₀ and λ₂ were selected for calibration using a dual-annealing global optimization algorithm. The optimized values were α₀ = 128.216 and λ₂ = 6.514.

Calibration substantially improved model performance. The model reproduced NH₄⁺ dynamics reasonably well during the calibration period but showed reduced predictive performance during validation, particularly under variable wet-weather conditions.

## My Contribution

This project was completed as part of a four-person group.

I was primarily responsible for Tasks 3.1, 3.2, and 3.5, including:

- Selection and justification of the optimization method
- Selection of sensitive parameters for calibration
- Model calibration using dual annealing
- Selection of calibration and validation datasets
- Estimation and interpretation of optimized parameter values
- Evaluation of calibration quality and parameter bounds
- Assessment of model performance after calibration
- Contribution to report writing, figures, and quality control

## Skills Demonstrated

- Environmental model calibration
- Parameter estimation
- Global optimization
- Dual annealing
- Sensitivity-analysis interpretation
- Calibration and validation
- Model performance assessment
- RMSE-based evaluation
- Wastewater modelling
- Scientific data analysis
- Scientific visualisation
- Model uncertainty assessment

## Course

**12104 Environmental Modelling**  
Technical University of Denmark (DTU)

---

*This repository contains a portfolio-oriented summary of the project rather than the original course assignment.*
