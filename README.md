# 📘 K-Nearest Neighbors (KNN) Classification - Iris Dataset

## 🔍 Objective
Implement and understand the K-Nearest Neighbors (KNN) algorithm for solving classification problems using the Iris dataset. This project demonstrates how to train a KNN classifier, evaluate its performance, and visualize decision boundaries.

---

## 🛠 Tools & Libraries Used
- Python 3.x
- [Scikit-learn](https://scikit-learn.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- NumPy

---

## 📁 Files
- `knn_iris_classification.py`: Main script containing all steps of the KNN classification pipeline.

---

## 📊 Dataset
- **Iris Dataset**: A classic dataset in machine learning that contains 150 samples of 3 species of iris flowers (*Setosa*, *Versicolor*, *Virginica*), with 4 features each.
- The script uses only the first 2 features (`sepal length`, `sepal width`) for visualization purposes.

---

## ✅ Features Implemented
1. **Data Loading**: Loads the Iris dataset from Scikit-learn.
2. **Data Preprocessing**: 
   - Feature selection (first two features for visualization).
   - Train-test split.
   - Feature normalization using `StandardScaler`.
3. **Model Training**:
   - Trains KNN models for `k = 1, 3, 5, 7`.
4. **Evaluation**:
   - Computes and displays **accuracy** and **confusion matrix** for each value of `k`.
5. **Visualization**:
   - Plots **confusion matrices**.
   - Plots **decision boundary** for `k = 3`.

---

## ▶️ How to Run
1. Install required libraries if not already installed:

   ```bash
   pip install numpy pandas matplotlib scikit-learn
