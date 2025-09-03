# Bank Marketing – Decision Tree Classifier

This project implements a Decision Tree Classifier on the Bank Marketing Dataset
 from the UCI Machine Learning Repository.

The goal is to predict whether a customer will subscribe to a term deposit (yes/no) based on their demographic and behavioral data.

📂 Dataset

Source: UCI ML Repository – Bank Marketing

Size: ~41,000 records, 20+ features

Target Variable:

y → Customer subscribed? (yes / no)

Example Features:

age, job, marital, education

default, balance, housing, loan

contact, day, month, duration, campaign, etc.

🧹 Data Preprocessing

Replaced "unknown" values with NaN and handled missing data.

Encoded categorical variables using Label Encoding.

Split dataset into train (80%) and test (20%) sets.

🌳 Model – Decision Tree Classifier

Algorithm: DecisionTreeClassifier (Scikit-learn)

Hyperparameters:

criterion="entropy"

max_depth=5

min_samples_split=20

📊 Results

Evaluation Metrics:

Accuracy

Precision, Recall, F1-score

Confusion Matrix

Feature Importance (Top predictors):

duration (last contact duration)

poutcome (previous campaign outcome)

age

balance

📈 Visualizations

Confusion Matrix Heatmap

Feature Importance Barplot

Decision Tree Plot (showing rules and splits)

⚙️ Tech Stack

Python 3.x

Pandas, NumPy – Data handling

Matplotlib, Seaborn – Visualization

Scikit-learn – ML model
