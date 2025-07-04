# 🏦 Bank Customer Churn Prediction

## 📌 Introduction
Customer churn, or attrition, is the phenomenon where customers stop using a company's products or services over a specified period. In the banking sector, churn typically refers to clients closing their accounts or ceasing to use the bank's services.

Customer churn is a significant concern for banks because acquiring new customers is often far more costly than retaining existing ones. High churn rates can negatively impact profitability, customer loyalty, and brand reputation, making it crucial for banks to understand and mitigate the factors driving churn.

## 🎯 Why Predicting Churn is Important

### ✅ Cost Efficiency
Acquiring new customers involves substantial marketing and operational expenses. In contrast, retaining existing customers is more cost-effective. By predicting churn, banks can prioritize retention strategies for at-risk clients, thus reducing overall customer acquisition costs.

### ✅ Increased Customer Lifetime Value (CLV)
Retained customers bring sustained revenue and profits over time. By reducing churn, banks improve CLV through long-term engagement and satisfaction.

### ✅ Personalized Customer Retention Strategies
Predictive models identify which customers are at risk and why. This enables banks to create highly targeted and personalized strategies—offers, communications, and service enhancements—to retain those customers.

### ✅ Proactive Decision-Making
Churn prediction allows for early intervention through loyalty programs, tailored offers, or improved customer service—preventing customer loss before it occurs.

### ✅ Data-Driven Insights
Models reveal key churn drivers such as poor service experience, competition, or financial changes. These insights can guide banks in improving service quality and reducing systemic issues.

## 📊 Dataset

- **Source**: [Kaggle – Bank Customer Churn Dataset](https://www.kaggle.com/datasets/radheshyamkollipara/bank-customer-churn)
- **Description**: This dataset contains demographic and financial data of bank customers, including features that may contribute to customer churn behavior.

## 🧠 Model Selection & Evaluation

In the context of imbalanced datasets, traditional accuracy is not reliable on its own. Metrics such as:
- **Precision**
- **Recall**
- **F1-Score**
- **ROC-AUC Score**

…are more informative for evaluating performance.

After training several machine learning models and comparing them using the **ROC-AUC Score**, the best-performing model was:

> **✅ Logistic Regression**  
> **ROC-AUC Score: 0.9996**

This score indicates excellent performance in distinguishing between churn and non-churn customers.


