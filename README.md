# 🌸 Iris Flower Classification using Random Forest

## 📌 Project Overview
This project implements a Machine Learning classification model to predict Iris flower species using the Random Forest algorithm.

The model classifies flowers into three categories:
- Iris-setosa
- Iris-versicolor
- Iris-virginica

The prediction is based on four numerical features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

---

## 🛠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

---

## 🔍 Machine Learning Workflow
1. Loaded training and test datasets.
2. Separated features (X) and target variable (y).
3. Trained a RandomForestClassifier model.
4. Predicted flower species on unseen test data.
5. Evaluated model performance using accuracy calculation.

---

## 📊 Model Performance
The Random Forest model achieved **97.05% accuracy** on the test dataset.
The DecisionTreeClassifier achieved **97.05% accuracy** on the test dataset.
The GaussianNB achieved **97.05% accuracy** on the test dataset.

Accuracy was calculated both:
- Manually using a loop comparison.
- Using `sklearn.metrics.accuracy_score`.

This indicates strong classification performance across the three Iris species.

---

## 🧠 Key Learnings
- Understanding supervised learning workflow.
- Train-test dataset separation.
- Difference between Pandas DataFrame and NumPy arrays.
- How scikit-learn handles categorical labels internally.
- Importance of proper execution order in Jupyter Notebook.

---

## 🚀 Future Improvements
- Add confusion matrix visualization.
- Perform hyperparameter tuning.
- Compare with other algorithms (Logistic Regression, SVM).
- Implement cross-validation.

---

## 📎 About
This project was developed as part of strengthening foundational Machine Learning skills and understanding model evaluation techniques.
