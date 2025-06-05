# 🧠 Breast Cancer Classification using Support Vector Machines (SVM)

This project demonstrates how to use **Support Vector Machines (SVM)** for classifying breast cancer tumors as **malignant** or **benign** using the `breast-cancer.csv` dataset.

We implement both **linear** and **non-linear (RBF kernel)** SVMs, evaluate their performance, tune hyperparameters, and visualize decision boundaries using PCA.

---

## 📁 Dataset

The dataset used is based on the [Breast Cancer Wisconsin (Diagnostic) Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).

- Features: 30 numeric features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass.
- Target: `diagnosis` (M = malignant, B = benign)

---

## 🛠️ Tools & Libraries

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 🚀 Project Structure

| Section | Description |
|--------|-------------|
| 📦 Data Loading       | Load and preprocess the CSV dataset |
| 🧹 Preprocessing       | Encode target, scale features |
| 🧠 Model Training      | Train SVM with linear and RBF kernels |
| 🧪 Evaluation          | Classification report, confusion matrix |
| 🔍 Cross-Validation   | 5-fold CV for model stability |
| 🎯 Hyperparameter Tuning | Grid Search for `C`, `gamma`, and `kernel` |
| 🧭 Visualization       | PCA-based 2D decision boundary plots |

---

## 📊 Results

| Model        | CV Accuracy | Comments |
|--------------|-------------|----------|
| Linear SVM   | ~XX.XX%     | Simpler, interpretable decision boundary |
| RBF SVM      | ~XX.XX%     | Captures non-linear patterns better |
| Best Model (Grid Search) | ~XX.XX% | Tuned for optimal performance |

> Replace `XX.XX%` with your actual results after running the notebook.

---

## 📈 Visualizations

- PCA-based projection to 2D for plotting decision boundaries
- Clear separation of classes shown using contour plots and scatter overlays

