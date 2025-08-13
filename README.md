# Hybrid Brain-Age Prediction Model for Neuroimaging Data

## Overview
This repository hosts the **trained TabTransformer-GPR model** for brain-age prediction using structural MRI-derived morphometric features. The model was designed to address limitations in existing brain-age models by combining:
- **TabTransformer** for learning complex feature interactions in tabular data  
- **Gaussian Process Regression (GPR)** for uncertainty estimation and improved generalization  

Our approach achieved **state-of-the-art performance** on multiple independent datasets and demonstrated robust prediction across the lifespan (ages 2–95 years).

## Features
- Trained on **25,425 healthy controls** across multiple global neuroimaging sites
- Input: **288 morphometric features** extracted via FreeSurfer (cortical thickness, surface area, volume, white matter volumes, and subcortical volumes)
- Output: Predicted brain age in years
- Supports **age-bias correction** for Brain-PAD computation
- Model interpretability via **SHAP analysis**

