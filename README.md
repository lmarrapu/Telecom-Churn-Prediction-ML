# 📡 ChurnEra - Predictive Modeling for Telecom Customer Retention 📊

## 🎯 Project Objective

The goal of this project is to:
- Analyze the key factors driving customer churn in the telecom sector.
- Develop predictive models to forecast churn effectively.
- Propose strategies for customer retention using data-driven insights.

---

## 📂 Dataset Overview

The project leverages the **Telco Customer Churn Dataset**, which contains:
- Customer demographics: Gender, SeniorCitizen, Partner, Dependents
- Subscription details: Tenure, PhoneService, InternetService, PaymentMethod
- Usage metrics: MonthlyCharges, TotalCharges
- Churn indicator: Whether the customer has churned or not

The dataset is analyzed to identify patterns and trends influencing churn behavior.

---

## 🧪 Methodology

The project follows these steps:
1. **📊 Exploratory Data Analysis (EDA):** Analyze trends, detect outliers, and visualize churn patterns.
2. **🛠️ Feature Engineering:** Create meaningful features like interaction terms and perform dimensionality reduction (PCA).
3. **📈 Model Development:** Train, evaluate, and compare various machine learning models.
4. **⚙️ Model Optimization:** Fine-tune hyperparameters for enhanced performance.
5. **📊 Results Analysis:** Compare model outcomes using key metrics.

---

## 🚀 Models Explored

A variety of statistical learning approaches were evaluated for churn prediction:
- **Logistic Regression**: Baseline and forward selection
- **Random Forest**: With and without PCA
- **Support Vector Machines (SVM)**: With regularization and cost optimization
- **Decision Trees**: Enhanced with pruning
- **Linear Discriminant Analysis (LDA)**
- **Naive Bayes**: Bootstrapped for evaluation

---

## 🏆 Key Findings

- Customers with **shorter tenure, higher monthly charges, and lower total charges** are more likely to churn.
- **Fiber Optic users** and those using **Electronic Check** as a payment method show higher churn rates.
- Feature interactions and advanced regularization techniques improved model performance.
- **Random Forest and SVM models** demonstrated the highest predictive accuracy.

## 🚀 Models and Results

| **Model**                    | **Accuracy** | **Precision** | **Recall** | **F1-Score** | **AUC**  |
|-------------------------------|--------------|---------------|------------|--------------|----------|
| Logistic Regression           | 81%          | 68%           | 58%        | 62%          | 74%      |
| Random Forest (Tuned)         | 80%          | 83%           | 92%        | 87%          | 70%      |
| SVM (Regularized)             | 81%          | 84%           | 91%        | 88%          | 72%      |
| Decision Tree (Pruned)        | 80%          | 81%           | 94%        | 87%          | 76%      |
| Naive Bayes                   | 77%          | 88%           | 80%        | 84%          | 75%      |

The **Regularized SVM** and **Tuned Random Forest** emerged as top-performing models for predicting churn.

---
## 🛠 Tools and Technologies

- **Programming Language:** R
- **Libraries Used:** `tidyverse`, `randomForest`, `caret`, `ggplot2`, `e1071`, and more.
- **Techniques:** Cross-validation, bootstrapping, feature selection, and hyperparameter tuning.

---

## 🔮 Future Work

- Implement **ensemble methods** like Gradient Boosting and Stacking.
- Use **SHAP values** to interpret feature importance.
- Enhance recall for models like Naive Bayes to capture more churn cases.
- Expand the dataset for broader generalization.

---

## 📜 Conclusion

The **ChurnEra** project demonstrates the potential of machine learning in solving real-world challenges. By identifying key factors influencing churn and employing robust predictive models, we can empower telecom companies to reduce customer attrition and foster long-term growth. 🌐

---

## 📫 Contact

For questions or collaboration opportunities, feel free to reach out!

---

### ⭐️ **If you find this repository useful, give it a star!** ⭐️
