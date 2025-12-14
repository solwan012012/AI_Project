# AI_Project
Student Performance Analysis & Prediction using Machine Learning
📖 Project Description

This project focuses on analyzing and predicting student academic performance using machine learning techniques.
The dataset used contains detailed information about students’ personal, social, and academic attributes, collected from secondary school students in Portugal.

The main objective of the project is to:
Understand the factors that affect students’ final grades.
Apply different machine learning models to predict student performance.
Compare model performance using appropriate evaluation metrics.
Visualize data distributions, relationships, and model behavior.

📊 Dataset Description

The dataset consists of two student datasets:
Mathematics students/Portuguese language students/Both datasets are merged and include features such as:
Demographic information (age, gender, family status)/Parents’ education and jobs/Study habits and lifestyle
Alcohol consumption/Absences/Previous grades (G1, G2)
Final grade (G3) → target variable

📌 G3 represents the final grade of the student (ranging from 0 to 20).

⚙️ Data Preprocessing
The following preprocessing steps were applied:
Merging datasets and shuffling data
Handling categorical features using One-Hot Encoding
Scaling numerical features using StandardScaler
Separating features and target variable
Splitting data into training and testing sets

🤖 Machine Learning Models Used

K-Nearest Neighbors (KNN)
Tested different values of k and analyzed performance using accuracy and confusion matrix.

Linear Regression
Used to predict final grades (G3), evaluated with R², MAE, MSE, RMSE, and residual analysis.

Logistic Regression
Applied for pass/fail classification, evaluated using accuracy, confusion matrix, ROC–AUC, and precision-recall curves.

Random Forest Classifier
Used for binary classification with feature importance analysis and performance evaluation metrics.

Support Vector Machine (SVM)
Applied for classification and evaluated using accuracy and confusion matrix.

🧠 Key Insights
Previous grades (G1 and G2) are the strongest predictors of final performance.
Academic habits and family-related features also influence student success.
Classification models perform well when predicting pass/fail outcomes.
Random Forest provides strong performance and clear feature importance insights.
