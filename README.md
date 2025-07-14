📌 Project Title: Student Performance Prediction using ML
📄 Description
This project uses supervised machine learning algorithms to predict whether a student will pass or fail based on their exam scores and other attributes such as gender, lunch type, and test preparation. The goal is to explore multiple classification algorithms and compare their performance.

📊 Dataset
Source: Kaggle – Students Performance in Exams
Rows: 1000
Columns: Gender, Race/Ethnicity, Parental Education, Lunch, Test Preparation, Math Score, Reading Score, Writing Score.

✅ Project Steps
1.Data Cleaning & Preprocessing
Handled categorical features using label encoding
Created a binary target variable passed (1 = pass, 0 = fail) based on average score

2.Train-Test Split
80% training / 20% testing

3.Algorithms Used
Logistic Regression
Decision Tree
Random Forest
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)

4. Evaluation Metrics
Accuracy
Precision, Recall, F1-Score
Confusion Matrix

📈 Results
Most models achieved similar accuracy due to the simplicity of the dataset
Random Forest and SVM gave slightly better stability and precision
Visualization of confusion matrices was used for detailed error analysis


