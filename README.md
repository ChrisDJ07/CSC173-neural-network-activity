# 🧠 Neural Network From Scratch (Python + NumPy)

## Members
- CHRISTIAN DAVE JANIOLA
- HUSSAM BANSAO
- NATHANIEL BALANAY

## 📘 Overview
This project builds a simple **neural network from scratch** using only **Python and NumPy** (no ML libraries like TensorFlow, PyTorch, or scikit-learn models).  
We trained it to classify **breast cancer tumors** as malignant or benign.

## Requirements
- Make sure you have: `pip install numpy matplotlib scikit-learn
`
- Run the notebook
  - Open the .ipynb notebook (or paste into Google Colab) and run all cells.

---

## 🧩 Dataset
- **Source:** [Scikit-learn Breast Cancer Dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html)
- **Classes:**  
  - `0` → Malignant  
  - `1` → Benign

### Features used
We used two selected features for visualization and simplicity:

Feature 0: `mean radius`

Feature 1: `mean texture`

You can change them in the code:
```python
feat_idx = [0, 1]  # mean radius and mean texture
```
## Implementation Details
Implemented manually:

- Random weight initialization

- Forward propagation (matrix computations)

- Activation functions

- Mean Squared Error loss

- Backpropagation (manual gradient computation)

- Parameter updates with gradient descent

## Visualization:

- Training loss plot

- Decision boundary (for 2D inputs)

## Results

Train accuracy: `0.9055`, Test accuracy: `0.8596`

Loss per hundred iterations:
```
Iter 1/1000 — loss: 0.204422
Iter 200/1000 — loss: 0.112362
Iter 400/1000 — loss: 0.088395
Iter 600/1000 — loss: 0.078742
Iter 800/1000 — loss: 0.073664
Iter 1000/1000 — loss: 0.070550
```