README file for Capstone Project

The goal of the capstone project is to find whether the credit card transaction is fraudulent or not. 

Data source : Please download creditcard.csv file from following link ( the size is 150.83 MB ): 
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The Suketu_Shah_Capstone_Project _EDA.IPYNB file provides the primary data analysis information.

Suketu_Shah_Capstone_Project.IPYNB has following steps:
1. Data load
2. EDA
3. Data pre-processing
4. Following models were created and compared
		a. Deep learning neural network
		b. Random forest
		c. Decision tree
		d. KNN
		e. Deep learning neural network using SMOTE
		
As data is very imbalanced as there are very few fraudulent transactions compared to valid transactions.
SMOTE was used to solve that problem with oversampling.
The main purpose is to have minimum false negatives, so, any fraud transaction can not go undetected. 
This creates more false positives, which may increase the effort to check false transactions.