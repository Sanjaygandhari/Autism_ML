# Autism_Prediction_App
Project_Overview:
    This project focuses on leveraging Machine Learning (ML) algorithms to screen for Autism Spectrum Condition (ASC) in children efficiently and accurately. Early diagnosis of ASC is critical for timely intervention, and this system aims to reduce waiting times by providing a quick and accessible preliminary screening tool.

Key_Features:
Input Method: Users respond to a series of binary questions (Yes = 1, No = 0) regarding behavioral and developmental traits.
Algorithms: Includes models such as Decision Tree, Random Forest, Naïve Bayes, Support Vector Machine (SVM), and Gradient Boosting.
Best Performing Model: Gradient Boosting with an accuracy of 96.55%.
Deployment: The model is deployed on a web application using Streamlit, allowing users to input responses and get the probability of ASC.

Technical_Highlights:
Dataset: Compiled from multiple online sources, containing 1346 records with attributes like behavioral responses, age, gender, and familial factors.
Tools Used:Programming Language: Python.
Libraries: Pandas, NumPy, Scikit-learn, Streamlit.
Steps Involved:
1.Data preprocessing and feature engineering.
2.Training and testing multiple ML models.
3.Deploying the best model to a user-friendly web app.

How_It_Works:
1.Users answer 10 behavioral questions and provide 5 demographic details.
2.The responses are processed by the ML model.
3.The app outputs a probability score, indicating the likelihood of ASC.
Future_Scope:
1.Integrate more extensive datasets to improve model robustness.
2.Expand the system's capabilities by incorporating additional behavioral and demographic factors.
