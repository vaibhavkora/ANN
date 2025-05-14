# Customer Churn Prediction Using Artificial Neural Network (ANN) 🚀

## Overview 🌟
This project builds an Artificial Neural Network (ANN) to predict customer churn for a bank using the `Churn_Modelling.csv` dataset. It classifies whether a customer will leave (`Exited=1`) or stay (`Exited=0`) based on demographic and financial features. Developed in a Jupyter Notebook (`ANN.ipynb`) using TensorFlow and Python libraries, it’s perfect for machine learning enthusiasts and data scientists exploring binary classification! 🧠💻

## 📂 Dataset
The `Churn_Modelling.csv` dataset includes 10,000 customer records with the following features:

- `RowNumber`: Record number 🔢
- `CustomerId`: Unique ID 🆔
- `Surname`: Last name ✍️
- `CreditScore`: Credit score 📈
- `Geography`: Country (France, Spain, Germany) 🌍
- `Gender`: Male/Female 🚻
- `Age`: Customer age 🎂
- `Tenure`: Years with bank ⏳
- `Balance`: Account balance 💰
- `NumOfProducts`: Bank products used 🏦
- `HasCrCard`: Credit card status (`1=Yes`, `0=No`) 💳
- `IsActiveMember`: Active member status (`1=Yes`, `0=No`) ✅
- `EstimatedSalary`: Annual salary estimate 💸
- `Exited`: Churn status (`1=Churned`, `0=Retained`) 🚪

Stored in Google Drive (`/content/drive/MyDrive/Datasets/Churn_Modelling.csv`) for Colab access. 📂

## 🛠️ Project Structure
The notebook (`ANN.ipynb`) is organized into clear steps:

1. **Library Imports** 📚
   - TensorFlow for ANN 🧠
   - Pandas, NumPy, Matplotlib, Seaborn for data and visualization 📊
   - Scikit-learn for metrics 📏

2. **Data Loading & Exploration** 🔍
   - Loads dataset with `pd.read_csv()`
   - Displays first 5 rows with `df.head()`

3. **Feature Selection** ⚙️
   - Splits data into features (`X: CreditScore to EstimatedSalary`) and target (`y: Exited`)
   - Verifies data integrity using `X.head()`

4. **Model Prediction & Evaluation** 🏆
   - Uses a pre-trained ANN (`classifier`) to predict on `X_test`
   - Converts probabilities to binary (`y_pred > 0.5`)
   - Creates a confusion matrix
   - Calculates accuracy: **85.55%** 🎯

## ✨ Key Features
- **Data Preprocessing**: Feature selection and encoding ✂️
- **ANN Model**: TensorFlow-based neural network 🕸️
- **Evaluation**: Confusion matrix and accuracy 📈
- **Visualization**: Ready for Matplotlib/Seaborn plots 🎨
- **Reproducible**: Runs in Google Colab ☁️

## 🛠️ Dependencies
- Python 3.x 🐍
- TensorFlow (2.18.0) 🧠
- Pandas 📊
- NumPy 🔢
- Matplotlib 📈
- Seaborn 🎨
- Scikit-learn 📏

## ⚙️ Installation
```bash
git clone https://github.com/your-username/customer-churn-prediction-ann.git
pip install tensorflow pandas numpy matplotlib seaborn scikit-learn
