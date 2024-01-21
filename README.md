# Annual-Sales-Report-2022
## Overview Of Project:
Vrinda Store wants to create an (Annual Sales Report for 2022)
The primary goal of this project is to analyse and interpret the sales data for the VRinda Store over 2022. By doing so, the project aims to provide valuable insights that can guide strategic decision-making for the store's growth in 2024.This Analysis will Help Vrinda Store to better understand its customers and grow in 2023.
## Objectives:
- They want to compare the sales and orders using a single chart.
- Which month got the highest sales and orders?
- Who purchased more between Men and Women in 2022?
- What are the different order statuses in 2022?
- List the top 10 states contributing to sales in 2022 
- Which channel is contributing to max sales?
- Highest selling category?   
## Methodology:
- Data Collection: For the Annual Sales Report of Vrinda Store 2022, we collected our data from a comprehensive Kaggle dataset. Kaggle, a platform for predictive modelling and analytics competitions, provided a rich source of information related to retail and sales.
- Data Cleaning And Preprocessing: It's the process of taking raw, messy information and turning it into something reliable, consistent, and ready for analysis. Here are some key components of data cleaning and preprocessing.Data cleaning meticulously checks for errors, inconsistencies, and formatting issues to ensure the data's accuracy, completeness, and trustworthiness.
Preprocessing techniques strategically fill in missing values, remove duplicates, and identify and address outliers, ensuring a cohesive and reliable dataset.
- Sales Trends Analysis:Examine overall sales trends throughout the year with the help of a dashboard 
## Dataset: https://www.kaggle.com/datasets/anshika2301/vrinda-store-data-analysis?select=Store+Data.xlsx
## Observations From EDA:
1. 27 % of customers switched to another firm
2. Both genders behaved in similar fashion when it comes to migrating to another service provider/firm.
3. About 43% of customer with Month-to-Month Contract opted to move out as compared to 11% of customrs with One Year Contract and 3% with Two Year Contract.
4. Customers who use Fiber optic have high churn rate, this might suggest a dissatisfaction with this type of internet service. Customers having DSL service are majority in number and have less churn rate 
   compared to Fibre optic service.
5. Customers without dependents are more likely to churn.
6. Most customers churn due to lack of online security
7. Customers with Paperless Billing are most likely to churn.
8. Customers with no TechSupport are most likely to migrate to another service provider.


## Final Model:
We have used Logistic Regression, Decision Tree and Random Forest for Model Development. Based on the evaluation of models, we will select Logistic Regression for making predictions as it has accuracy of about 80% and better recall and precision value than the other two models.







