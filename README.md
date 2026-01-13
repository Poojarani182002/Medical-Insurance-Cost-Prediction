# Medical-Insurance-Cost-Prediction

Medical Insurance Cost Prediction Using Machine Learning
📌 Project Overview

This project aims to predict the medical insurance cost (charges) of a person based on their personal and health-related information such as age, gender, BMI, number of children, smoking habits, and residential region.
Using machine learning, we build a regression model that helps insurance companies estimate how much premium a customer should pay.

🎯 Objectives

Analyze how different factors affect insurance charges

Build a machine learning model to predict medical insurance cost

Help insurance companies make fair and data-driven pricing decisions

📊 Dataset

The dataset contains customer information such as:

Age

Gender

BMI (Body Mass Index)

Number of children

Smoking status

Region

Insurance charges

This dataset is used to train and evaluate the prediction model.

🛠 Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

Jupyter Notebook

🔍 Project Workflow

Data Collection
Load the medical insurance dataset.

Data Understanding & Cleaning
Check for missing values, data types, and outliers.

Exploratory Data Analysis (EDA)
Analyze relationships between features like age, BMI, smoking status, and insurance charges.

Data Preprocessing
Convert categorical variables (gender, smoker, region) into numerical form using one-hot encoding.

Train–Test Split
Split the dataset into training and testing sets.

Model Training
Train a Linear Regression model on the training data.

Model Evaluation
Evaluate the model using metrics like R² score, MAE, and RMSE.

Prediction
Use the trained model to predict insurance cost for new customers.

📈 Results

The model successfully predicts insurance charges based on customer data.
It clearly shows that:

Smoking has the strongest impact on insurance cost

Age and BMI also significantly affect the charges
