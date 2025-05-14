# Customer Churn Prediction Using Artificial Neural Network (ANN) 🚀

## 🌟Overview

This project builds an Artificial Neural Network (ANN) to predict customer churn for a bank using the "Churn_Modelling.csv" dataset. It classifies whether a customer will leave (Exited=1) or stay (Exited=0) based on demographic and financial features. Developed in a Jupyter Notebook (ANN.ipynb) using TensorFlow and Python libraries, it’s perfect for machine learning enthusiasts and data scientists exploring binary classification! 🧠💻

## 📊Dataset
The "Churn_Modelling.csv" dataset includes 10,000 customer records with features like:

**RowNumber**: Record number 🔢
**CustomerId**: Unique ID 🆔
**Surname**: Last name ✍️
**CreditScore**: Credit score 📈
**Geography**: Country (France, Spain, Germany) 🌍
**Gender**: Male/Female 🚻
**Age**: Customer age 🎂
**Tenure**: Years with bank ⏳
**Balance**: Account balance 💰
**NumOfProducts**: Bank products used 🏦
**HasCrCard**: Credit card status (1=Yes, 0=No) 💳
**IsActiveMember**: Active member status (1=Yes, 0=No) ✅
**EstimatedSalary**: Annual salary estimate 💸
**Exited**: Churn status (1=Churned, 0=Retained) 🚪

## 🛠️Project Structure 
The notebook is organized into clear steps:

1. **Library Imports 📚:**
       - TensorFlow for ANN 🧠
       - Pandas, NumPy, Matplotlib, Seaborn for data and visualization 📊
       - Scikit-learn for metrics 📏
2. **TensorFlow Version Check ✅:**
       - Confirms TensorFlow 2.18.0 for compatibility.
3. **Data Loading & Exploration 🔍:**
       - Loads dataset with pd.read_csv() 📖
       - Displays first 5 rows with df.head() 👀
4. **Feature Selection ⚙️:**
      - Splits data into features (X: CreditScore to EstimatedSalary) and target (y: Exited).
      - Shows X.head() for verification.
5. **Model Prediction & Evaluation 🏆:**
     - Uses a pre-trained ANN (classifier) to predict on X_test 🔮
     - Converts probabilities to binary (y_pred > 0.5) ✔️
     - Creates confusion matrix: [[1515, 80], [209, 196]] 📉
     - True Negatives: 1515 ✅
     - False Positives: 80 ❌
     - False Negatives: 209 ❌
     - True Positives: 196 ✅
     - Calculates accuracy: 85.55% 🎯
     - Retrieves model weights for analysis 🧮 

    
