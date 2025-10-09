# 🧠 Neural Network From Scratch (Python + NumPy)

## Members
- CHRISTIAN DAVE JANIOLA
- HUSSAM BANSAO
- NATHANIEL BALANAY

## 📘 Overview
This project builds a simple **neural network from scratch** using only **Python and NumPy** (no ML libraries like TensorFlow, PyTorch, or scikit-learn models).  
We trained it to classify **breast cancer tumors** as malignant or benign.

---

## 🧩 Dataset
- **Source:** [Scikit-learn Breast Cancer Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)
- **Classes:**  
  - `0` → Malignant  
  - `1` → Benign

### Features used
We only use **two features** for simplicity and visualization:
```python
feat_idx = [0, 1]  # mean radius and mean texture
