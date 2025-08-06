# ❤️ Heart Disease Prediction Project

This project applies and compares various Machine Learning algorithms to predict heart disease from clinical data. It aims to help understand how different models perform in terms of accuracy, interpretability, and speed.

---

##  Dataset

- **Source:** [Kaggle - Heart Failure Prediction](https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction)
- **Features:** Age, Sex, Chest Pain Type, Resting BP, Cholesterol, Max HR, etc.
- **Target:** `HeartDisease` (0 = No, 1 = Yes)

---

##  Objectives

- Explore and visualize the dataset
- Apply **feature engineering** and **scaling**
- Train and evaluate multiple ML models
- Understand performance, speed, and interpretability trade-offs
- Answer the key ML comparison questions

---

##  ML Models Compared

| Model              | Type              |
|-------------------|-------------------|
| Decision Tree      | Interpretable model |
| k-NN               | Lazy learner      |
| Support Vector Machine (SVM) | Margin-based classifier |
| Random Forest      | Ensemble (Bagging) |
| Gradient Boosting  | Ensemble (Boosting) |

---

##  Visualizations

- Correlation heatmap
- Pair plots by Heart Disease
- Box plots for numeric features
- Count plots for categorical features

---

## ✅ Results Summary

###  Which model performed best?
> Gradient Boosting showed the highest accuracy and F1 score.

###  Which model was fastest?
> Decision Tree and k-NN trained fastest.

###  Most interpretable?
> Decision Tree was easiest to interpret with a visual structure.

---

## 📁 Project Files

- `heart-disease-analysis.ipynb`: Main notebook
- `heart.csv`: Dataset
- `README.md`: Project documentation

---

## 🛠 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter/Colab Notebook

---

## 📌 License

This project is for educational and demonstration purposes only.
