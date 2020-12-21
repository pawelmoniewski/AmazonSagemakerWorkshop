# Amazon Sagemaker - AutoML  

In this lab, you will get hands-on with Amazon Sagemaker AutoML. An automated machine learning (commonly referred to as AutoML) solution for tabular datasets. You can use SageMaker Autopilot in different ways: on autopilo (hence the name) or with human guidance, without code through SageMaker Studio, or using the AWS SDKs.

Losing customers is costly for any business. Identifying unhappy customers early on gives you a chance to offer them incentives to stay. This lab describes using machine learning (ML) for the automated identification of unhappy customers, also known as customer churn prediction. We will use the same data set as we did in **Lab 1** as we are already familiar with it.  


# Setup

1. We will start with opening Notebook `autopilot_customer_churn.ipynb`. We will skip detailed instruction how to procees as you are the expert now.  
  
    
In case You did not follow this workshi in order, you can find detailed instruction how to complete this step [_“here”_](https://github.com/pawelmoniewski/AmazonSagemakerWorkshop/blob/main/Lab%201/README.md#data-preparation).  
  
  
2. In the very first two cells we will start with specifying:  
  
  - The S3 bucket and prefix that you want to use for training and model data. Replace the appropriate variable names according to your preferences.