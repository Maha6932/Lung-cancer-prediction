
# 🩺 Lung Cancer Survival Prediction using Machine Learning

This project applies **Logistic Regression, Decision Tree, and Random Forest** models to predict **lung cancer patient survival outcomes** using clinical data, aiming to identify key prognostic factors and support personalized, data-driven treatment planning.

---

## 📌 Project Objective

- Develop and compare predictive models to estimate **treatment outcomes and survival probabilities** in lung cancer patients.
- Identify key predictors, such as **AJCC stage, smoking status, and treatment type**, that influence survival.
- Support **personalized, data-driven clinical decision-making** in oncology.

---

## 🩻 Data Overview

The dataset includes:

- **Vital Status** (Alive/Dead) – Target variable.
- **AJCC Pathologic Stage** (I, II, III, IV with subcategories).
- **Treatment Type** (Chemotherapy, Radiation, Surgery, etc.).
- **Tobacco Smoking Status** (Non-Smoker, Current Smoker, Reformed Smoker).
- **Demographics** (Gender, Race).
- Additional variables like **age at diagnosis** and **pack years smoked**.

Data preprocessing involved **cleaning missing values, recoding categories, and preparing the dataset for modeling**.

---

## 🤖 Models Used

1️⃣ **Logistic Regression** – A simple, interpretable linear baseline.  
2️⃣ **Decision Tree** – Captures non-linear patterns, easy to explain.  
3️⃣ **Random Forest** – An ensemble model offering high prediction accuracy and feature importance insights.

---

## 🧪 Evaluation Metrics

To compare model performance, the following metrics were used:

- **Accuracy**
- **Sensitivity (Recall)**
- **Specificity**
- **Precision**
- **F1 Score**
- **AUC (Area Under ROC Curve)**

---

## 📊 Results

| Metric      | Logistic Regression | Decision Tree | Random Forest |
|-------------|----------------------|---------------|---------------|
| Accuracy    | 29%                  | 72%           | **82%**       |
| Sensitivity | 27%                  | 70%           | **80%**       |
| Specificity | 32%                  | 73%           | **83%**       |
| Precision   | 35%                  | 63%           | **78%**       |
| F1 Score    | 30%                  | 66%           | **79%**       |
| AUC         | 0.70                 | 0.71          | **0.81**      |

✅ **Random Forest achieved the best performance across all evaluation metrics.**

---

## 📈 Visualizations

- **Kaplan-Meier Survival Curves:** Analyzed survival probabilities by AJCC stages, smoking status, and treatment types.
- **Feature Importance Plot:** Highlighted key predictors influencing survival.
- **ROC Curves:** Compared models visually for discrimination power.
- **Bar Graphs:** Compared metrics for all models.

---

## 🛠️ How to Run

1️⃣ **Clone this repository:**

```bash
git clone https://github.com/YourUsername/Lung-Cancer-Survival-Prediction.git
cd Lung-Cancer-Survival-Prediction
````

2️⃣ **Install required R packages:**

```r
install.packages(c("dplyr", "ggplot2", "caret", "randomForest", "survival", "survminer", "pROC", "tidyr", "broom"))
```

3️⃣ **Run the analysis scripts in the `/scripts` folder to replicate the workflow.**

---

## 🎯 Conclusion

This project demonstrates that **machine learning models, particularly Random Forest, can accurately predict lung cancer survival outcomes using clinical features**. It highlights the potential of using data-driven methods to assist personalized treatment planning, aligning with the goal of improving patient care in oncology.

---

## 📬 Contact

For questions or collaborations:

* **Mahalakshmi Aranganathan**
* \mahalakshmi.aranga@gmail.com
* \https://www.linkedin.com/in/mahalakshmi-aranganathan/

---

## ⭐ Acknowledgments

This project was developed as part of **STAT 5353: Probability and statistics for data science and Bioinformatics** to demonstrate practical applications of machine learning in healthcare analytics.

---

```

---
