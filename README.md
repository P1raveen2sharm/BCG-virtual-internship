## BCG-virtual-internship

#Customer Churn Prediction: Comprehensive Summary
Customer churn prediction is essential for businesses to retain customers and reduce revenue loss. This project aims to develop a machine learning model to identify high-risk customers based on their consumption patterns, pricing sensitivity, and contract details. The importance of this project lies in its potential to enable proactive customer retention strategies, optimize pricing models, and enhance long-term business sustainability.

The dataset consists of two primary sources: Client Data (14,606 records, 26 features) containing customer details, contract information, and churn labels, and Price Data (193,002 records, 8 features) capturing historical pricing trends. Initial exploratory data analysis (EDA) revealed that 9.7% of customers churned, and that churn is influenced by factors such as tenure, contract modifications, and price fluctuations. Additionally, categorical variables required encoding, and numerical variables showed high skewness, necessitating transformations.

For data preprocessing and feature engineering, missing values were handled, categorical variables were transformed into numerical representations, and new features were engineered to enhance predictive power. Key features included tenure calculation, price sensitivity metrics, contract renewal timelines, and rolling consumption trends. Logarithmic transformations were applied to normalize skewed data, and feature selection was performed to optimize model performance.

A machine learning model was trained using Logistic Regression and Decision Trees, with evaluation metrics such as accuracy, precision, recall, and F1-score. The findings showed that customers with a tenure of less than four months were significantly more likely to churn, and those with multi-service contracts (electricity + gas) had a 2% lower churn rate. Additionally, price-sensitive customers exhibited higher churn rates, indicating that dynamic pricing strategies could play a crucial role in retention.

From a business perspective, this model provides actionable insights for targeted retention campaigns, allowing businesses to identify high-risk customers and offer personalized discounts or incentives. By optimizing pricing and contract structures, the company can reduce churn, improve customer lifetime value, and enhance overall profitability. Further refinements, such as incorporating additional customer behavior data and deploying the model for real-time predictions, could further improve its impact.








