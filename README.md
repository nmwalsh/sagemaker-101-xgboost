# sagemaker-101-xgboost
Build, train, and deploy a bank enrollment predictor with Amazon SageMaker and XGBoost

Original workshop available from [AWS tutorials](https://aws.amazon.com/getting-started/tutorials/build-train-deploy-machine-learning-model-sagemaker/).

## Build, Train, and Deploy a Machine Learning Model with Amazon SageMaker

In this tutorial, you will learn how to use Amazon SageMaker to build, train, and deploy a machine learning (ML) model. We will use the popular XGBoost ML algorithm for this exercise. Amazon SageMaker is a modular, fully managed machine learning service that enables developers and data scientists to build, train, and deploy ML models at scale.

Taking ML models from conceptualization to production is typically complex and time-consuming. You have to manage large amounts of data to train the model, choose the best algorithm for training it, manage the compute capacity while training it, and then deploy the model into a production environment. Amazon SageMaker reduces this complexity by making it much easier to build and deploy ML models. After you choose the right algorithms and frameworks from the wide range of choices available, it manages all of the underlying infrastructure to train your model at petabyte scale, and deploy it to production.

In this tutorial, you will assume the role of a machine learning developer working at a bank. You have been asked to develop a machine learning model to predict whether a customer will enroll for a certificate of deposit (CD). The model will be trained on the marketing dataset that contains information on customer demographics, responses to marketing events, and external factors.

The data has been labeled for your convenience and a column in the dataset identifies whether the customer is enrolled for a product offered by the bank. A version of this dataset is publicly available from the ML repository curated by the University of California, Irvine. This tutorial implements a supervised machine learning model since the data is labeled. (Unsupervised learning occurs when the datasets are not labeled.)
