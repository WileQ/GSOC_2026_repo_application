# DeepLense project application GSOC 2026

## Overview

The DeepLense project is a deep learning pipeline for particle dark matter searches with strong gravitational lensing. In order to participate in this project, I submit the two required tasks. One is the common test and the other Quantum ML test for the "Hybrid Quantum-Classical Representation Learning for Dark Matter Substructure Classification" project.

## Summary of Results

Below are the results achieved in each task.

### Common test

| Metric | ResNet | DenseNet | EffNet| 
| :--- | :--- | :--- |:---| 
| **AUC Score - No** | 0.99 | 0.98 | 0.97| 
| **AUC Score - Sphere** | 0.97 | 0.97 | 0.94| 
| **AUC Score - Vort** | 0.99 | 0.99 | 0.96| 
| **No substructure F1-Score** | 0.92 | 0.92 | 0.87| 
| **Vortex substructure F1-Score** | 0.88 | 0.88 | 0.82| 
| **Subhalo substructure F1-Score** | 0.92 | 0.93 | 0.85| 
| **Accuracy** | 0.91 | 0.91 | 0.85| 

Best ROC curve:
![ROC Curve ResNet 50](Code_basic_task/plots/densenet-roc.png)


### Quantum ml test

| Metric | Quantum |
| :--- | :--- |
| **AUC Score - No** | 0.83 |
| **AUC Score - Sphere** | 0.71 |
| **AUC Score - Vort** | 0.71 |
| **No substructure F1-Score** | 0.66 |
| **Vortex substructure F1-Score** | 0.49 |
| **Subhalo substructure F1-Score** | 0.49 |
| **Accuracy** | 0.56 |

Best ROC curve:
![ROC Curve Quantum](Quantum_ml/plots/quantum-roc.png)
