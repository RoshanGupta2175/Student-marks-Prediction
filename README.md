📘 Student Marks Prediction – Machine Learning Project
📌 Overview

This project builds an end-to-end machine learning model to predict a student’s final exam score based on study hours, sleep duration, attendance, and previous performance. The goal is to understand how different factors influence academic results and to implement the full ML pipeline from data analysis to prediction.

🎯 Problem Statement

Given several attributes of a student, predict the final score.
Since the output is numerical, this is a regression problem.

🧠 Skills Demonstrated

Data loading and preprocessing

Exploratory Data Analysis (EDA)

Feature and target separation

Train-test splitting

Model training using Linear Regression

Performance evaluation

Future prediction on new data

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

📂 Dataset Features

study_hours – hours spent studying

sleep_hours – daily sleep duration

attendance – attendance percentage

previous_score – earlier exam marks

final_score – target variable

📊 Exploratory Data Analysis

EDA was performed to understand relationships between variables.
Correlation heatmaps and scatter plots showed that study hours and previous scores have strong influence on final performance.

🤖 Model Used

Linear Regression was used to learn the relationship between input features and the final score.

📏 Model Evaluation

Mean Absolute Error (MAE): ~5

R² Score: ~0.79

These results indicate the model predictions are close to actual values and capture most of the variance.

🔮 Future Prediction

The trained model can take details of a new student and estimate the expected final marks.

Example input:

study_hours = 6
sleep_hours = 7
attendance = 85
previous_score = 70

🚀 Learning Outcome

This project helped me understand the complete machine learning lifecycle:
data understanding → visualization → model building → evaluation → prediction.

🙋‍♂️ Author

Roshan Gupta

I am continuously learning and building projects in Data Science and Machine Learning.
Feedback and suggestions are welcome!
