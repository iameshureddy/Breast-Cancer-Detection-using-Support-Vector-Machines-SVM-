# 🧠 Breast Cancer Detection using Support Vector Machines (SVM)

This project demonstrates how to use **Support Vector Machines** with both **linear** and **non-linear (RBF)** kernels to classify breast cancer tumors as malignant or benign using the **Breast Cancer Wisconsin dataset**.

---

## 📊 Dataset

- Source: [Kaggle - Breast Cancer Dataset](https://www.kaggle.com/datasets/yasserh/breast-cancer-dataset)
- Attributes: 30 numeric features + 1 diagnosis label
- Classes: Malignant (1), Benign (0)

---

## ✅ What this Project Covers

- Data Preprocessing and Feature Scaling
- Training SVM with Linear and RBF Kernels
- Hyperparameter Tuning (C and gamma)
- Cross-validation performance
- 2D Visualization using PCA
- Decision boundary plots

---

## 🧪 Models Trained

| Model        | Accuracy (CV) |
|--------------|---------------|
| Linear SVM   | ~96%          |
| RBF SVM (Tuned) | ~97%       |

---

## 📸 Visual Outputs

| Linear SVM | RBF SVM |
|------------|---------|
| ![](outputs/decision_boundary_linear.png) | ![](outputs/decision_boundary_rbf.png) |

---

## 🛠 Tools & Libraries

- Python
- Scikit-learn
- NumPy
- Pandas
- Matplotlib, Seaborn

---

## 🔍 Interview Questions Cheat Sheet

1. **What is a support vector?**  
   Data points closest to the decision boundary that influence the margin.

2. **What does the C parameter do?**  
   Controls trade-off between margin width and classification error.

3. **What are kernels in SVM?**  
   Functions to transform input space to make it linearly separable.

4. **Difference between linear and RBF kernel?**  
   Linear = straight hyperplane; RBF = curved, nonlinear boundary.

5. **Advantages of SVM?**  
   Effective in high-dimensional space, memory-efficient, versatile.

6. **Can SVMs be used for regression?**  
   Yes, with SVR (Support Vector Regression).

7. **When data is not linearly separable?**  
   Use kernel trick to transform space.

8. **How is overfitting handled?**  
   Through C and kernel parameters, and by using cross-validation.

---

## 📂 How to Run

```bash
pip install -r requirements.txt
python svm_classification.py
