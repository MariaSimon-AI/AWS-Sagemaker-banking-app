# AWS-Sagemaker-banking-app
This is a beginner level project for learning how to use AWS Sagemeker instance, S3 buckets and different APIs.

The model is trained on the Bank Marketing Data Set that contains information on customer demographics, responses to marketing events, and external factors. A version of this dataset is publicly available from the Machine Learning Repository curated by the University of California, Irvine

In this project, I learned how to:

1.	Create a SageMaker notebook instance
Imported necessary libraries and created S3 bucket

2.	Prepare the data
Downloaded the data and stored in S3 bucket. Then data is loaded to dataframe. Then the data is split to train and test sets and saved into buckets

3.	Train the model to learn from the data 
Model is build with Xgboot- Inbuilt Algorithm by specifying the XGBoost image URI. A SageMaker estimator is constructed by calling the xgboost-container . Then training job is initiated

4.	Deploy the model
Deployment of model as endpoints and predictions are made on test data

5.	Evaluate your ML model's performance. 
Confusion Matrix is used to evaluate the performance. Then the endpoints are deleted, buckets are deleted and instance is stopped.

