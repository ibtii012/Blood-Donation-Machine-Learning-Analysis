# Blood Donation Machine Learning Analysis

## Overview
This project analyzes blood donation patterns to predict whether individuals will donate blood in the future.  
It leverages **machine learning techniques** to provide actionable insights for healthcare organizations and blood banks to optimize donor engagement and campaigns.

---

## Dataset
**Blood Donation Dataset**  

Includes:  
- **Demographic Features:** Age, gender  
- **Donation History:** Number of donations, months since last donation  
- **Target Variable:** Whether the donor will donate in the next period  

**Preprocessing Steps:**  
- Handled missing values  
- Normalized numerical features  
- Encoded categorical variables  

---

## 1- Predicting Blood Donations
**Objective:** Predict whether a donor will donate in the future.

**Methodology:**  
- Tested **Logistic Regression, Decision Tree, Random Forest, and SVM**  
- Applied feature scaling and class balancing  

**Model Performance:**  
- Random Forest: **~85% accuracy**  
- Logistic Regression: ~78%  
- Decision Tree: ~74%  

**Feature Insights:**  
- Number of previous donations and recency are strongest predictors  
- Demographics moderately influence outcomes  

**Practical Use:**  
- Helps blood banks **target likely donors**  
- Optimizes blood donation campaigns  

---

## 2- Model Evaluation
- **Confusion Matrix**  
- **Classification Report** (Precision, Recall, F1-score)  
- **ROC Curve and AUC**  

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
