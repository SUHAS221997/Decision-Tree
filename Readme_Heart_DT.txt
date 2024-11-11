Heart Disease Prediction using Decision Tree Classifier

Overview:
This project uses a Decision Tree Classifier to predict the presence of heart disease based on a set of patient features. The model classifies individuals as either having heart disease or not having heart disease based on attributes such as age, sex, blood pressure, cholesterol levels, and other medical indicators.

Objective:
•	Goal: Predict the likelihood of heart disease in a patient based on their health attributes using a Decision Tree Classifier.
•	Dataset: The project uses the Heart Disease dataset, which is widely used in machine learning for binary classification tasks.
•	Model: The classifier is trained using a Decision Tree model, which provides an interpretable structure to understand decision-making based on the features.

Dataset:
The dataset contains medical data for several patients, including both numerical and categorical features. The target variable is target, where:
•	0 represents no heart disease.
•	1 represents presence of heart disease.

Features:
•	age: Age of the patient.
•	sex: Gender of the patient (1 = male, 0 = female).
•	cp: Chest pain type (categorical).
•	trestbps: Resting blood pressure (mm Hg).
•	chol: Serum cholesterol level (mg/dl).
•	fbs: Fasting blood sugar level (1 = true, 0 = false).
•	restecg: Resting electrocardiographic results (categorical).
•	thalach: Maximum heart rate achieved.
•	exang: Exercise induced angina (1 = yes, 0 = no).
•	oldpeak: ST depression induced by exercise relative to rest.
•	slope: Slope of the peak exercise ST segment.
•	ca: Number of major vessels colored by fluoroscopy.
•	thal: Thalassemia (categorical).
•	target: Whether the patient has heart disease (1 = yes, 0 = no).

How It Works:
The Decision Tree algorithm is used to classify whether a person is at risk of heart disease or not. The tree makes decisions based on feature splits, where each split represents a decision rule on one of the input features. The goal is to minimize the impurity (e.g., Gini impurity or entropy) at each split, leading to the most accurate predictions.

Steps:
1.	Data Loading: Load the dataset and inspect the data.
2.	Data Preprocessing: Handle missing values, encode categorical features, and scale numerical features if necessary.
3.	Train/Test Split: Split the dataset into training and testing sets to evaluate the model's performance.
4.	Model Training: Train the Decision Tree classifier using the training data.
5.	Model Evaluation: Evaluate the trained model's performance on the test set using metrics such as accuracy, precision, recall, and F1-score.
6.	Visualize the Tree: Optionally, visualize the trained decision tree to understand how the model makes predictions.
