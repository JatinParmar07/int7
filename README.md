# int7

# Support Vector Machine (SVM) Binary Classification Project

## Objective

This project demonstrates the use of Support Vector Machines (SVM) for binary classification using both **linear** and **RBF kernels**. It includes data preparation, model training, visualization, hyperparameter tuning, and performance evaluation.

---

## Project Steps

### 1. Load and Prepare the Dataset
- Imported Breast Cancer Detectiom dataset for binary classification (i.e., two target classes).
- Scaled features to ensure effective SVM training.
- Splitted the dataset into **training** and **testing** subsets.

---

### 2. Train SVM with Linear and RBF Kernels
- Trained two SVM models:
  - One with a **linear kernel**, which assumes data is linearly separable.
  - One with an **RBF (Radial Basis Function) kernel**, which captures non-linear patterns in the data.
- Fitted both models on the training set.

---

### 3. Visualize Decision Boundary Using 2D Data
- Reduced data to 2 dimensions using **PCA**.
- Plotted the decision boundary to illustrate how the SVM separates the two classes.

---

### 4. Tune Hyperparameters (C and Gamma)
- Used techniques such as **Grid Search** or **Randomized Search** to find the best values of:
  - **C**: Regularization parameter (controls margin softness).
  - **Gamma** (for RBF kernel): Defines how far the influence of a single training example reaches.


---

### 5. Evaluate Performance Using Cross-Validation
- Applied **k-fold cross-validation** to measure generalization performance of the model.
- Selected the best model based on cross-validation results.

---

## Output
- Decision boundary plots for linear and RBF kernels.
- Best hyperparameter values found via tuning.
- Cross-validation scores summarizing model performance.


