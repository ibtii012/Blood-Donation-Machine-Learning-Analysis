# Blood Donation Machine Learning Analysis

## Overview
This project analyzes blood donation patterns to predict whether individuals will donate blood in the future.  
It leverages **machine learning techniques** to provide actionable insights for healthcare organizations and blood banks to optimize donor engagement and campaigns.

---

## Dataset
**Blood Donation Dataset**  

Source: [Blood Transfusion Service Center Dataset](https://archive.ics.uci.edu/ml/datasets/blood+transfusion+service+center)  


Includes:  
- **Demographic Features:** Age, gender  
- **Donation History:** Number of donations, months since last donation  
- **Target Variable:** Whether the donor will donate in the next period  

**Preprocessing Steps:**  
- Handled missing values  
- Normalized numerical features  
- Encoded categorical variables  

---

## 1️⃣ Predicting Blood Donations
**Objective:** Predict whether a donor will donate in the future.

**Methodology:**  
- Tested **Logistic Regression, Decision Tree, Random Forest, and SVM**  
- Applied feature scaling and class balancing  

**Model Performance:**  
- Random Forest: **~85% accuracy** ✅  

**Feature Insights:**  
- ![Correlation Circle](images/Correlation%20Circle.png)
- ![Feature Importance](images/Feature%20Importance.png)

**Practical Use:**  
- Helps blood banks **target likely donors**  
- Optimizes blood donation campaigns  

---

## 2️⃣ Model Evaluation
- ![Model Performance](images/Model%20Performance.png)  
- ![Confusion Matrix](images/Confusion%20Matrix.png)  

**Takeaways:**  
- Ensemble models outperform single classifiers  
- Proper preprocessing improves predictive accuracy  

---

## Tools & Libraries
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · Logistic Regression · Random Forest · Decision Tree · SVM  

---

## Future Directions
- Include additional donor behavior and demographic features  
- Explore deep learning models for more complex patterns  
- Segment donors for **personalized campaigns**  

---

## About
Machine learning analysis of blood donation patterns using classification and ensemble methods to predict future donations, identify key features, and provide actionable insights for healthcare organizations.

---
