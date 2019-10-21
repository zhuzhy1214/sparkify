# sparkify
This is a sample project to identify potential churn users based on user activities, using pyspark.

The goal is to train a binary classifier to identify users (in both free and paid tier) who might the Sparkify music streaming service, based on the patterns obtained from their past activity and interaction with the service. 


## Approach
This notebook is arranged based on the following approach:
1. Data exploration: to understand the data, find data distribution and boundaries, find data anormaly and etc.
2. Data wrangling: to clean data, derive data,visualize and summarize data
3. Feature engineering: to define and generate features and label to be used in the model training, create train and test data set.
4. Model training and evaluation: develop a few pilot models, define evaluation metrics for the model. Conduct initial evaluation for the model.
5. Model tuning and conclusion: conduct parametric search to find best hyperparameters, and conduct model evaluation with final conclusion. 


## Files:
-sparkify.ipynb 
-output images
--action_distribution.png
--correlation.png
--gender_effect.png


The project used a tiny subset (128MB) to conduct data analyaia and develop the model, and the full dataset available (12GB) to train and validate model.

Detailed writeup about the findings are available at: 
https://medium.com/@zhenyuzhu/identify-potential-churn-users-for-sparkify-22c5c52974b1




