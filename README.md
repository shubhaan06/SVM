# 📊 SVM Parameter Optimization - Human Activity Recognition

This project focuses on optimizing Support Vector Machine (SVM) parameters (kernel, C, gamma) using a multi-class classification dataset from the UCI Machine Learning Repository.

---

## 📁 Dataset

- **Name**: Human Activity Recognition Using Smartphones  
- **Source**: [UCI Repository](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones)  
- **Samples**: 10,299  
- **Features**: 561 (numeric)  
- **Classes**: 6 (e.g., walking, sitting, laying, etc.)

---

## 🧪 Objective

- Perform parameter optimization of SVM classifiers using different kernels (`rbf`, `linear`, `poly`, `sigmoid`)
- Apply 10 different 70-30 random train-test splits
- Run 100 random hyperparameter samples per split
- Record best parameters and accuracy per split
- Visualize convergence (accuracy vs. iteration) for the best-performing split

---

## 💻Table


| Sample | Best Accuracy | Best SVM Parameters (Kernel, C, Gamma)          |
|--------|----------------|--------------------------------------------------|
| S1     | 98.77%         | linear, C=1.1286, gamma=0.01024                 |
| S2     | 98.41%         | poly, C=6.5589, gamma=0.04476                   |
| S3     | 98.64%         | linear, C=2.2875, gamma=0.05796                 |
| S4     | 98.64%         | poly, C=6.5589, gamma=0.04476                   |
| S5     | 98.71%         | poly, C=6.5589, gamma=0.04476                   |
| S6     | 98.35%         | linear, C=2.2875, gamma=0.05796                 |
| S7     | 98.71%         | poly, C=6.5589, gamma=0.04476                   |
| S8     | 98.67%         | linear, C=1.262, gamma=0.0777                   |
| S9     | 98.41%         | linear, C=1.6897, gamma=0.01204                 |
| S10    | 98.61%         | linear, C=1.6897, gamma=0.01204                 |



## 📈Graph

![convergence_plot](https://github.com/user-attachments/assets/7ae9c1e5-d4a2-4be7-96a3-c8a31bacf4bd)



