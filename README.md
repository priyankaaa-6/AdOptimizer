# AdOptimizer
**Introduction**: 
This project aims to develop a dashboard for analyzing ad performance across various platforms and reallocating budgets based on predicted conversions. The solution includes data processing, model training, and budget allocation based on user input and predictive analytics.

**Libraries and Versions**: 
The following libraries are used in this project:
•	pandas: 2.2.2
•	scikit-learn: 1.4.2
•	seaborn: 0.11.2
•	matplotlib: 3.8.4
•	dash: 2.17.1
•	plotly: 5.22.0
To install these libraries, you can use the following commands:
%pip install pandas==2.2.2
%pip install scikit-learn==1.4.2
%pip install seaborn==0.11.2
%pip install matplotlib==3.8.4
%pip install dash==2.17.1
%pip install plotly==5.22.0

**Datasets**: 
The project utilizes two main datasets:
Dataset 1: It contains performance metrics for Google Ads, Meta Ads, and Facebook Ads. Dataset 2: It contains performance metrics for Google Ads, Meta Ads, Facebook Ads, and Microsoft Ads.

**Algorithm**: 
•	Linear Regression: Used to predict conversions based on impressions, clicks, cost, CTR, and CPC.
•	Random Forest Regressor: Applied to capture non-linear relationships and improve prediction accuracy.
•	Gradient Boosting Regressor: Employed for further boosting the prediction performance.

**Conclusion**: 
The dashboard effectively allocates budgets across different ad platforms based on predicted conversions and provides interactive visualizations. Future improvements could include more sophisticated models for prediction and additional features for scenario analysis.

