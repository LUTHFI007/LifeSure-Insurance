# LifeSure-Insurance

## Group Members:
- Luthfi Juneeda Shaj  
- Sandeep Pidugu  
- Sethulakshmi Kochuchirayil Babu  
- Yasar Thajudheen  
- Yunhao Zhou  

## Project Overview
The rapid growth of artificial intelligence in various industries has highlighted the importance of transparency and interpretability in AI-driven decision-making. This project focuses on AI explainability within the insurance sector, specifically in pricing and marketing campaign effectiveness.

## Key Objectives
- Enhance transparency in AI predictions for insurance pricing and marketing.
- Identify key features influencing model outputs.
- Develop an interactive dashboard for better interpretability.

## Data Preprocessing
Before training machine learning models, we applied the following preprocessing techniques:
- **Handling Missing Data**: Median imputation for missing values (e.g., income).
- **Encoding Categorical Variables**: One-hot encoding for categorical features.
- **Sampling**: Selected a subset of 1338 records for computational efficiency.
- **Merging Datasets**: Combined insurance and marketing campaign data using age as the key.

## Correlation Analysis
A correlation matrix was generated to explore relationships between variables. Notably:
- **Strong correlations** were found between income, age, insurance charges, and marketing response rates.
- Insights from this analysis guided feature selection for predictive modeling.

## Analysis of Insurance Charges and Marketing Campaigns
### Insurance Charges:
- **Smoker status** significantly increased insurance costs.
- **Regional differences** in charges indicated external influencing factors.

### Marketing Campaign Effectiveness:
- Analyzed customer responses to identify engagement patterns.
- Factors like previous interactions, income levels, and spending habits influenced marketing success.

## Customer Segmentation
Customers were grouped based on their spending behavior and marketing engagement to tailor marketing strategies.

## Predictive Modeling
Machine learning models were built to predict both insurance charges and marketing campaign responses:

### Models Implemented:
- **Random Forest**
- **LightGBM**
- **XGBoost**

### Best Model Selection:
- **Insurance Charge Prediction**: Random Forest achieved the lowest Mean Squared Error (MSE) of 368,585.
- **Marketing Campaign Response Prediction**: LightGBM provided the best accuracy and efficiency.

## Feature Importance Analysis
Understanding key factors influencing predictions:
- **Insurance charges**: Smoking status, Age, BMI.
- **Marketing responses**: Previous campaign interactions, Income, Spending behavior.

## Interactive Dashboard
To enhance AI explainability, we built an interactive dashboard allowing users to:
- Visualize key feature influences on model predictions.
- Apply dynamic filters for customized analysis.

## Conclusion
Explainability is crucial for trust in AI systems, especially in high-stakes domains like insurance. This project successfully identified significant predictive factors and developed an interpretable AI framework. Future improvements may include refining feature selection and integrating advanced explainability techniques.
