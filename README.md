# Credit Risk Analysis Using Python & Machine Learning

## Project Overview
This project analyzes borrower and loan information to identify patterns associated with loan defaults. It uses Exploratory Data Analysis (EDA) and Machine Learning classification models to understand credit risk and support data-driven lending decisions.

## Objectives
- Analyze borrower and loan characteristics.
- Identify factors associated with loan defaults.
- Perform data cleaning and exploratory data analysis.
- Build and evaluate machine learning classification models.
- Generate actionable business insights.

## Dataset
- Source: [Kaggle – Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset)
- Records: 32,581 originally
- Features: 12
- Target variable: `loan_status`
  - 0 – Non-default
  - 1 – Default

## Tools & Technologies
- Python
- Google Colab
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Machine Learning

## Project Workflow
1. Data loading and inspection
2. Data cleaning and preprocessing
3. Exploratory Data Analysis
4. Feature encoding and scaling
5. Train-test splitting
6. Logistic Regression modelling
7. Balanced Logistic Regression modelling
8. Random Forest classification
9. Model evaluation
10. Feature importance analysis
11. Business insights and recommendations

## Model Performance

| Model | Accuracy | Precision | Recall | F1-score | ROC-AUC |
|---|---:|---:|---:|---:|---:|
| Logistic Regression | 86.91% | 77.28% | 56.84% | 65.50% | 86.80% |
| Balanced Logistic Regression | 81.51% | 55.56% | 77.22% | 64.62% | 86.96% |
| Random Forest | 93.21% | 95.62% | 72.28% | 82.33% | 93.10% |

**Best overall model:** Random Forest, based on its F1-score and ROC-AUC among the evaluated models.

## Key Business Insights
- Overall loan default rate was 21.87%.
- Loan grade G recorded the highest observed default rate at 98.44%.
- Debt consolidation loans had the highest default rate among loan purposes at 28.68%.
- Defaulting borrowers had a higher average loan-to-income ratio (0.247) compared with non-defaulting borrowers (0.149).
- Loan-to-income ratio and personal income were among the most influential model features.

## Business Recommendations
- Monitor borrowers with higher loan-to-income ratios.
- Conduct additional risk assessments for higher-risk loan categories.
- Investigate default patterns across loan purposes.
- Use predictive analytics to support credit risk assessment.

## Limitations
- The model is based on historical data and is not a production-ready lending system.
- Feature availability at the time of loan approval must be verified to prevent data leakage.
- Model predictions should support responsible human decision-making.

## Conclusion
This project demonstrates how Python, exploratory data analysis and machine learning can be applied to credit risk assessment. The analysis identified important borrower and loan characteristics associated with defaults, while model comparison showed the potential of Random Forest for predicting credit risk.

## Author
Thennarasi

MSc Data Science | Data Analyst Aspirant
