# 🚀 Spaceship Titanic – Machine Learning Classification Project

This project was submitted to the [Kaggle Spaceship Titanic competition](https://www.kaggle.com/competitions/spaceship-titanic), a classification challenge focused on predicting the fate of passengers affected by a space-time anomaly aboard an interstellar ship.

📊 **Final Score:** `0.80289` (Kaggle Public Leaderboard)

---

## 🔍 Project Summary

- Built an end to end classification pipeline using Python and XGBoost
- Conducted data analysis to identify patterns and inconsistencies
- Engineered new features to capture spatial, social, and behavioral dynamics
- Applied custom data cleaning strategies to handle missing or contradictory values
- Tuned model hyperparameters and evaluated performance through iterative testing

---

## 🧠 Tools & Techniques Used

- **Python (Pandas, NumPy)**: Data manipulation and wrangling
- **Scikit-learn**: Label encoding, cross-validation, pipeline utilities
- **XGBoost**: Gradient-boosted decision trees for classification
- **Matplotlib**: Visualized feature importance for insight and debugging
- **Feature Engineering**:
  - Aggregated spending behavior
  - Inferred group travel context from IDs
  - Extracted and combined location details (e.g., cabin deck and side)
  - Adjusted values based on logical dependencies (e.g., CryoSleep + spending)

---

## 📦 Workflow Overview

1. **Data Preprocessing**
   - Cleaned and imputed missing values using context-aware strategies
   - Transformed categorical features using label encoding
   - Validated data assumptions and adjusted for outliers

2. **Feature Engineering**
   - Created interaction features to capture spatial and group patterns
   - Derived relative and contextual variables from existing fields
   - Binned continuous features to improve categorical separation

3. **Model Development**
   - Used XGBoost for its strong performance on structured data
   - Tuned learning parameters to balance bias and variance
   - Monitored feature importance to guide feature selection and iteration

4. **Evaluation & Submission**
   - Validated results using cross-validation
   - Submitted predictions to the Kaggle leaderboard
   - Iteratively improved based on feedback from scores and visual diagnostics

---

## 📁 Repository Contents

| File                        | Description                             |
|-----------------------------|-----------------------------------------|
| `DataTitanic_v4.py`         | Final version of the modeling pipeline  |
| `README.md`                 | This document                           |
| `submission_spaceship_titanic_v4.csv` | Final Kaggle prediction file (optional) |

---

## 🎯 Key Takeaways

- Effective feature engineering can drastically improve model performance
- Real-world data often includes implicit relationships that aren’t immediately visible
- Clean, logical preprocessing is critical to ensure model generalization
- Iterative modeling and leaderboard feedback are excellent for skill development

