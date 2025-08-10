# Development of an AI-Based Melanoma Detection and Assessment System

This repository contains my thesis project focused on developing an AI-driven system for detecting and assessing melanoma using dermatoscopic images. It explores deep learning models built from scratch and via transfer learning.

## ​ Thesis PDF  
[Download the full thesis (PDF)](Deep-learning-Medical-SkinCancer-Thesis.pdf)

##  Objective  
Design and evaluate deep learning-based models for melanoma detection with clinical-level accuracy, aiding early clinical diagnosis.

##  Methodology  
1. **Preprocessing**: Image normalization, augmentation, class balancing.  
2. **Modeling**:  
   - Students Net (MATLAB) – from scratch  
   - AlexNet (MATLAB) – transfer learning  
   - Bayesian CNN (Python) – from scratch  
3. **Evaluation Metric**: F1-score (prioritized for its balance of precision and recall, key in medical diagnosis).

##  Results

| Technique                           | Training (%) | Validation (%) | Test (%) |
|-------------------------------------|--------------|----------------|----------|
| From Scratch – Students Net         | 80.90        | 80.07          | 80.57    |
| Transfer Learning – AlexNet         | 99.37        | 99.79          | 99.58    |
| From Scratch – Python (Bayesian)    | 97.72        | 93.17          | 93.26    |

Transfer Learning with AlexNet achieved the best performance (**99.58% F1-score on the test set**), closely followed by the Bayesian CNN in Python.


##  Future Work  
- Fullly migrating experiments to Python for reproducibility.  
- Integrating top models into a web-based diagnostic prototype.  
- Exploring other architectures (EfficientNet, Vision Transformers...).

##  Contact  
**Isaias Rojas M.**  
Email: rojas.isaiah.1998@gmail.com  
GitHub: [IsaiasRojasM](https://github.com/IsaiasRojasM)

##  Repository Structure

