# Machine Learning Labs & Portfolio

This repository contains practical implementations and conceptual evaluations of foundational machine learning algorithms. Projects are built from scratch and optimized using `scikit-learn`.

## 📂 Core Modules Covered

### 1. Linear & Polynomial Regression
- **Dataset:** California Housing
- **Key Concepts:** Ordinary Least Squares, gradient descent optimization, handling target caps/outliers, and interpreting learned feature coefficients ($w$ and $b$).

### 2. Logistic Regression & Classification
- **Dataset:** Breast Cancer Wisconsin
- **Key Concepts:** Sigmoid function mapping, binary cross-entropy optimization, threshold tuning (0.3, 0.5, 0.8), and balancing Precision vs. Recall.

### 3. Support Vector Machines (SVM)
- **Dataset:** Iris (Petal features)
- **Key Concepts:** Maximizing margins, isolating support vectors, feature scaling impacts, and comparing Linear vs. Radial Basis Function (RBF) non-linear kernels.

### 4. Decision Trees & Ensembles
- **Dataset:** Iris
- **Key Concepts:** Information Gain calculation via Gini Impurity and Entropy, tree depth constraints (`max_depth`), Random Forest bagging estimators, and Gradient Boosting learning rate tuning.

---

## 📊 Evaluation Metrics Applied
- **Regression:** Root Mean Squared Error (RMSE), $R^2$ Score.
- **Classification:** Confusion Matrices, Precision, Recall, F1-Score, and ROC-AUC curves.

## 🛠️ Tech Stack Used
- Python 3
- NumPy & Pandas (Data Manipulation)
- Scikit-Learn (Model Training & Evaluation)
- Matplotlib & Seaborn (Decision Boundary Visualization)
