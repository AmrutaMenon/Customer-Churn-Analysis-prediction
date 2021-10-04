# Telecom Customer Churn Analysis and Prediction

## Introduction

### What is Customer Churn?
Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service.
Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next. The telecommunications business has an annual churn rate of 15-25 percent in this highly competitive market.
Individualized customer retention is tough because most firms have a large number of customers and can't afford to devote much time to each of them. The costs would be too great, outweighing the additional revenue. However, if a corporation could forecast which customers are likely to leave ahead of time, it could focus customer retention efforts only on these "high risk" clients. The ultimate goal is to expand its coverage area and retrieve more customers’ loyalty. The core to succeed in this market lies in the customer itself.
Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers.

## Context
Predict the whether a customer churn or not by analyzing the behavior of different customers. Here we also analyze what are the reasons that make a customer to churn.

## Motivation
Different reasons trigger customers to terminate their contracts, for example better price offers, more interesting packages, bad service experiences or change of
customers’ personal situations. From an organizational perspective, it is always cheaper to retain existing customer than to spend money to acquire new customer. We want to use Machine Learning models to predict whether a customer will retain or not.

## Data Source
The dataset was collected from Kaggle named as Telco Customer Churn dataset. It was an IBM issued dataset.
Link: https://www.kaggle.com/blastchar/telco-customer-churn

## Content 
Each row in the dataset represents a customer, while each column contains customer’s attributes described on the column Metadata. The raw data contains 7043 rows (customers) and 21 columns (features). 

###Column names: 
* CustomerID: Customer ID unique for each customer.

* gender: Whether the customer is a male or a female.

* SeniorCitizen: Whether the customer is a senior citizen or not (1, 0).

* Partner: Whether the customer has a partner or not (Yes, No). 

* Dependent: Whether the customer has dependents or not (Yes, No). 

* PhoneService: Whether the customer has a phone service or not (Yes, No). 

* MultipeLines: Whether the customer has multiple lines or not (Yes, No, No phone service). 
 
* InternetService: Customer’s internet service provider (DSL, Fiber optic, No). 

* OnlineSecurity: Whether the customer has online security or not (Yes, No, No internet service). 
 
* OnlineBackup: Whether the customer has an online backup or not (Yes, No, No internet service). 
  
* DeviceProtection: Whether the customer has device protection or not (Yes, No, No internet service). 
   
* TechSupport: Whether the customer has tech support or not (Yes, No, No internet service). 
   
* StreamingTV: Whether the customer has streaming TV or not (Yes, No, No internet service). 
    
* StreamingMovies: Whether the customer has streaming movies or not (Yes, No, No internet service). 
      
* Contract: The contract term of the customer (Month-to-month, One year, Two years). 
       
* PaperlessBilling: The contract term of the customer (Month-to-month, One year, Two years). 
        
* PaymentMethod: The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).
         
* Tenure: Number of months the customer has stayed with the company. 
          
* MonthlyCharges: The amount charged to the customer monthly.  TotalCharges: The total amount charged to the customer. 
            
* Churn: Whether the customer churned or not (Yes or No).

## Methodology 
The methodologies explained in this project are data collection which has already been discussed. Now, we move to data preprocessing and data cleaning. Then comes the analysis part along with the visualization and afterwards the prediction was done based on the model created. 

* Data Collection
* Data Preprocessing and cleaning 
* Data Analysis and Visualization 
* Split dataset into train and test 
* Model selection and evaluation 
* Prediction

## Language
Python 3

## Libraries used
* Numpy
* Pandas
* Matplotlit
* Seaborb
* ScikitLearn

## Conclusion

After performing the analysis and applying different Machine Learning Algorithms, we can say that out of the three models, decision tree and logistic regression were more accurate in predicting the values and we were able to get an accuracy of 77%.
