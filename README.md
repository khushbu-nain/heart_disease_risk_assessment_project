# heart_disease_risk_assessment_project
# ❤️ Heart Disease Risk Assessment using Decision Tree & Random Forest

## 📌 Overview

Heart Disease Risk Assessment is a machine learning project that predicts the presence of heart disease using patient clinical data. The project compares the performance of **Decision Tree** and **Random Forest** classifiers and demonstrates a complete machine learning workflow—from data preprocessing and exploratory data analysis to model evaluation and feature importance analysis.

---

## 🎯 Objectives

- Predict the likelihood of heart disease using clinical features.
- Compare the performance of Decision Tree and Random Forest models.
- Analyze key factors influencing heart disease prediction.
- Build an end-to-end supervised machine learning pipeline.

---

## 📂 Dataset

**Dataset:** UCI Heart Disease Dataset (`heart_disease_uci.csv`)

| Feature | Details |
|---------|---------|
| Records | 920 Patients |
| Clinical Features | 15 |
| Task | Binary Classification |
| Target | 0 = No Disease, 1 = Disease Present |

---

## ⚙️ Project Workflow

- Data Preprocessing & Missing Value Handling
- Exploratory Data Analysis (EDA)
- Feature Encoding
- Train-Test Split
- Decision Tree Classification
- Random Forest Classification
- Model Evaluation
- Performance Comparison
- Feature Importance Analysis

---

## 🤖 Models Used

- Decision Tree Classifier
- Random Forest Classifier

### Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

## 📊 Results

The **Random Forest** model achieved better predictive performance than the Decision Tree model, reaching an accuracy of approximately **86%**, compared to **80%** for the Decision Tree.

**Top Predictive Features:**
- Chest Pain Type
- Thalassemia
- ST Depression (Oldpeak)
- Number of Major Vessels
- Age
- Maximum Heart Rate

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Getting Started

1. Clone this repository.
2. Place `heart_disease_uci.csv` in the project folder.
3. Install the required libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

4. Open `Heart_Disease_Risk_Assessment.ipynb`.
5. Run all notebook cells.

---

## 🔮 Future Enhancements

- Hyperparameter Tuning
- Cross-Validation
- XGBoost & LightGBM
- Model Deployment using Streamlit

---

## 👩‍💻 Author

**Khushbu Nain**  
**B.Tech – Computer Science Engineering (AI & Data Science)**

---

⭐ *If you found this project useful, consider giving this repository a star
