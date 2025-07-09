## Customer Response Prediction ##

This project analyzes and predicts which customers are most likely to respond to a direct marketing campaign, using data from the [Kaggle Customer Personality Analysis dataset](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis). The dataset includes customer demographics, purchase history, and past campaign interactions—enabling data-driven modeling of customer behavior and marketing outcomes.

# Goals
- Predict customer response to the latest marketing campaign  
- Identify high-value segments with strong engagement potential  
- Generate actionable insights to boost campaign ROI through modeling and visualization  

# Project Files
- `customer_response_prediction_25.ipynb`: Complete Colab notebook with EDA, feature engineering, model training, and insights  
- `marketing_campaign.csv`: Input dataset (original source from Kaggle)  
- `README.md`: Project overview and business context  

# Tools & Techniques
- Python (Pandas, Seaborn, Scikit-learn)  
- Models: Logistic Regression, Random Forest  
- Feature Engineering, Forward Feature Selection  
- ROC Curve Analysis, Threshold Tuning, Model Evaluation (AUC, Accuracy, Precision)  

# Key Findings
- **Customer Tenure**, **Spending Behavior**, and **Campaign History** are top predictors of campaign response  
- **Logistic Regression** outperformed Random Forest in both interpretability and test generalization (81.6% accuracy, 0.763 AUC)  
- Top 10 highest probability responders identified for campaign prioritization (e.g., 97% responder with $1,000+ spend)

# Business Impact
By accurately modeling customer response, this project enables smarter segmentation and campaign targeting—reducing marketing spend while increasing conversion rates. It empowers marketing teams to focus efforts on leads most likely to respond, improving ROI and decision-making with predictive insights.
