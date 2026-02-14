📘 Student Marks Prediction using Machine Learning
📌 Overview

This project develops an end-to-end Machine Learning pipeline to predict a student’s final exam score based on key academic and lifestyle factors such as study time, sleep duration, attendance, and previous performance.

The objective is to discover how these variables influence results and to transform raw data into accurate predictions.

🎯 Problem Statement

Given multiple attributes describing a student’s habits and academic history, predict the final exam marks.

Because the output is a continuous numeric value, the task is a regression problem.

🧠 Skills Demonstrated

✔ Data loading & preprocessing
✔ Exploratory Data Analysis (EDA)
✔ Feature engineering
✔ Train–test splitting
✔ Model training with Linear Regression
✔ Model performance evaluation
✔ Making predictions on unseen data

🛠️ Tech Stack

Python

Pandas

NumPy

Matplotlib / Seaborn

Scikit-learn

📂 Dataset Description
Feature	Description
study_hours	Number of hours spent studying
sleep_hours	Average daily sleep
attendance	Attendance percentage
previous_score	Marks obtained in earlier exams
final_score	🎯 Target variable to predict
📊 Exploratory Data Analysis (EDA)

Data visualization helped uncover patterns and relationships.

Students who studied more tended to score higher.

Previous performance showed strong correlation with final marks.

Attendance positively impacted outcomes.

Heatmaps and scatter plots made trends easy to observe.

🤖 Model Used – Linear Regression

Linear Regression was applied to learn how input variables influence final scores.

It finds the best mathematical relationship between features and the target to minimize prediction error.

📏 Model Evaluation

Mean Absolute Error (MAE): ~5 marks

R² Score: ~0.79

This means the model predicts very close to actual values and explains most of the variation in results.

🔮 Future Prediction


The trained model can estimate results for new students.

Code
  
Example Input:

study_hours = 6  
sleep_hours = 7  
attendance = 85  
previous_score = 70


➡ The system outputs the expected final exam score.

🚀 Learning Outcomes

Through this project, I gained practical understanding of the complete ML lifecycle:

Data → Analysis → Visualization → Training → Evaluation → Prediction

I also improved my skills in model interpretation and real-world problem solving.

🙋‍♂️ Author

Roshan Gupta

I am continuously learning and building projects in Data Science and Machine Learning.
Feedback, ideas, and collaboration are always welcome!
