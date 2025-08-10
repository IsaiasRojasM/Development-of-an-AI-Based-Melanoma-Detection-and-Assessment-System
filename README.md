# Development of an AI-Based Melanoma Detection and Assessment System

This repository contains my thesis project focused on the development of an artificial intelligence (AI) system for detecting and evaluating melanoma from medical images. The project explores different deep learning approaches, including models built from scratch and transfer learning.

## 📄 Thesis PDF
Download the full thesis:  
[Deep-learning-Medical-SkinCancer-Thesis.pdf](Deep-learning-Medical-SkinCancer-Thesis.pdf)

## 🎯 Objective
To design, implement, and evaluate deep learning models capable of detecting melanoma in dermatoscopic images with high accuracy, aiming to support early diagnosis in clinical settings.

## 🔬 Methodology
1. **Data Preprocessing**  
   - Image normalization  
   - Data augmentation  
   - Balancing classes  

2. **Model Development**  
   - From Scratch – Students Net (MATLAB)  
   - Transfer Learning – AlexNet (MATLAB)  
   - From Scratch – Bayesian CNN (Python)  

3. **Evaluation Metrics**  
   - F1-score  
   - Accuracy  
   - Sensitivity and specificity  

## 📊 Results

The models were evaluated using multiple performance metrics: **accuracy**, **sensitivity (recall)**, **precision**, **specificity**, and **F1-score**.  

For biomedical image classification, **F1-score** was chosen as the primary evaluation metric, as it balances both **precision** and **recall**, which is essential in medical diagnosis to reduce both false positives and false negatives.

The models were evaluated on training, validation, and test sets:


| Technique                           | Training (%) | Validation (%) | Test (%) |
|-------------------------------------|--------------|----------------|----------|
| From Scratch – Students Net         | 80.90        | 80.07          | 80.57    |
| Transfer Learning – AlexNet         | 99.37        | 99.79          | 99.58    |
| From Scratch – Python (Bayesian)    | 97.72        | 93.17          | 93.26    |

**Transfer Learning with AlexNet** achieved the highest performance, with **99.58% F1-score on the test set**, followed by the Bayesian CNN developed in Python.

## 📂 Repository Structure

## 🚀 Future Work
- Migrate all models to Python for easier reproducibility.  
- Integrate the best-performing model into a web-based diagnostic tool.  
- Explore other architectures (e.g., EfficientNet, Vision Transformers).

## 📬 Contact
If you have questions or want to collaborate:  
**Isaias Rojas M.**  
Email: rojas.isaiah.1998@gmail.com  
GitHub: [IsaiasRojasM](https://github.com/IsaiasRojasM)
