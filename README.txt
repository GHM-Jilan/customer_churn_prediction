Project Name: 
============
Ecommerce Customer Churn Analysis and Prediction


Source of Data: 
==============
Title	: Ecommerce Customer Churn Dataset
website : Kaggle 
url	: https://www.kaggle.com/datasets/ankitverma2010/ecommerce-customer-churn-analysis-and-prediction


Dataset Description: 
===================
A total of 20 features & 5630 records containing information about customers of an e-commerce company. 


Project Overview: 
================
Customer churn is the percentage of customers that stopped using a company's product or service during a certain period of time. Churn prediction means detecting which customers are likely to leave a service or to cancel a subscription to a service. It is a critical prediction for many businesses because acquiring new clients often costs more than retaining existing ones.

The dataset of the current study belongs to a leading online retail (E commerce) company. The company wants to know the customers who are going to churn, so that they can approach to the potential customers and offer them some promos and thus resist the potential Churn. 


Purpose of the Project:
======================
- To find out the features which have the most impact on the Churning of customers.
- To build a Machine Learning model in order to identify the potential customers, who are going to churn the company.


Requisite of the Project:
=========================
By applying this project E-commerce companies will be able to :
- Predict the customers who are likely to Churn.
- Understand the properties of customers, products or order which play key roles in Customer Churn.
- Understand why and what are the causes behind customers to leave and predict which customers are likely to leave. 
- Take better sales & marketing strategies to resist the Churn of customers, which eventually will foster the revenue of the company.


Project Completion Steps:
========================
1) Importing Necessary Libraries
2) Importing Dataset
3) Inspecting Dataset
4) Feature Engineering
5) Dealing with Missing Data
6) Exploratory Data Analysis (EDA)
7) Dealing with Outliers
8) Encoding of Features
9) Splitting Dataset into train, validation & test set
10) Feature Scaling
11) Building Classification Models
12) Cross Validation of the Models by validation data
13) Hyperparameter Tuning
14) Feature Importance Checking
15) Applying the final model (Random Forest Classification Model) on test data
16) Results
17) Key Findings of the Project


Key Findings of the Project at a glance:
=======================================
1) Mobile phone is more preferred login device than computer.

2) Among the 5 types of Payment Methods, Debit Card is the most preferred.

3) Among the 5 types of Order Categories, Mobile Phone is the dominant order category.

4) 50% of the customers registerd in 4 or less devices.

5) 75% of the customers spend 3 or less hours on App.

6) 75% of the customers used less than or equal to 2 No. of coupons.

7) 65% of the customers are from City Tier 1.

8) 71% of the customers provide complain.

9) Satisfaction Score increases when HoursSpendOnApp is less than 1 & greater than 2.

10) Mean Satisfaction Score = 3 (On a scale of 1 to 5).

11) Mean Order Count = 3 ; 50% of the customers order less than or equal to 2 No. of times.

12) Most of the customers are Male & married.

13) Mean order count of females are slightly more than men.

14) Divorced customers are slightly more satisfied than married and single customers.

15) Avg. order count from City Tier 3 is maximum.

16) OrderCount & CouponUsed is positively correlated with a coefficient of 0.65.

17) There is no significant correlation between Churn & Complain (0.25).

18) Among the 9 ML models, Random Forest Classifier was the best in performance. So, the final trained model was built upon the Random Forest Classifier.
 
19) The most important features regarding the prediction of Churn are 	Tenure, 
									CashbackAmount 
									WarehouseToHome
									NumberOfAddress &
									Complain

20) Our model is pretty great at Churn prediction with 	accuracy = 98%, 
							precision = 96%, 
							recall = 91%, 
							f1-score = 94% & 
							AUC = 0.99

