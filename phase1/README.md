# Phase 1: Exploratory Data Analysis & Baseline KNN

This directory contains **Phase 1** of the **mnist-knn-project**.  
In this phase, we introduce the MNIST handwritten digit dataset, perform exploratory data analysis (EDA) to understand its characteristics, and train a baseline classifier using **scikit-learn’s K-Nearest Neighbors (KNN)** algorithm.

---

## 📂 Contents
- **`mnist_eda.ipynb`** – Exploratory data analysis with visualizations, summary statistics, class distributions, and mean images for each digit.
- **`mnist_knn_sklearn.ipynb`** – Training and evaluating a KNN classifier using scikit-learn, establishing a baseline accuracy of ~97% on the test set.

---

## ⚙️ Requirements
- **Python** ≥ 3.8
- **Jupyter Notebook** or **JupyterLab**
- Python packages:
  - `numpy`
  - `pandas`
  - `matplotlib`
  - `scikit-learn`

Install the dependencies:
```bash
pip install numpy pandas matplotlib scikit-learn
```

---

## 🚀 Usage
1. Navigate to this directory:
   ```bash
   cd phase1
   ```
2. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open **`mnist_eda.ipynb`** to explore the dataset through visualizations and statistics.
4. Open **`mnist_knn_sklearn.ipynb`** to train and evaluate the baseline KNN model.

---

## 📊 Results
The baseline **scikit-learn KNN** model achieves approximately:
- **Accuracy:** ~97% on the MNIST test set
- Strong classification performance across all digits, with some confusion between visually similar digits (e.g., 4 and 9).

---

## 🔜 Next Steps
In the following phases, we will:
- **Phase 2:** Implement KNN from scratch using NumPy.
- **Phase 3:** Develop an interactive web application for real-time handwritten digit classification.
