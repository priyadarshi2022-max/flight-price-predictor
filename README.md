# ✈️ Flight Price Prediction using AWS SageMaker

This project demonstrates an end-to-end machine learning pipeline for flight price prediction using Amazon SageMaker. This project incorporates data preprocessing, model training, deployment, and cloud-native development.

## 🔍 Overview

- **Objective**: Predict flight ticket prices based on parameters such as airline, source, destination, departure time, duration, and more.
- **Platform**: AWS SageMaker for scalable training, S3 for data storage, EC2 for compute, IAM for access control.
- **Frontend**: Streamlit Web Application for interactive price prediction.

## 🧠 Key Concepts Learned

- AWS Services: SageMaker, EC2, S3, IAM
- Scikit-learn Pipelines: `Pipeline`, `ColumnTransformer`, `FunctionTransformer`, `FeatureUnion`
- Feature Engineering: Categorical encoding, duration extraction, handling missing values
- Model Deployment: Streamlit app hosted on cloud

## ⚙️ Workflow

1. AWS & SageMaker Setup
2. GitHub, Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering with custom transformers
5. Model Training, Hyperparameter Tuning, Deployment

> Note: Due to AWS charges, the model was trained on a subset of the data.

## 📸 Streamlit App
![Screenshot (196)](https://github.com/user-attachments/assets/1071722d-393f-49df-97fc-a2c14cf7fbba)
Just put in the values and inputs you want to see and then click the predict button to check the output result which is the predicted amount of the flight. 




