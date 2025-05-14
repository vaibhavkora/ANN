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
git clone https://github.com/vaibhavkora/Artificial_Neural_Network.git
pip install tensorflow pandas numpy matplotlib seaborn scikit-learn
 ```
## 🚀 Usage
- **Run the Notebook**: Execute cells in order ▶️  
- **Explore Data**: Check dataset structure with `df.head()` and `X.head()` 👀  
- **Evaluate Model**: Review confusion matrix and accuracy score 📊  
- **Extend**: Add preprocessing, visualizations, or hyperparameter tuning 🔧  

## 🎉 Results
- **Accuracy**: **85.55%** 🥳  
- **Confusion Matrix**: Strong non-churn prediction (1515 TN), with room to improve churn detection (196 TP) 📉  
- **Weights**: Provides insight into ANN’s learned patterns 🧮  

## 🔧 Potential Improvements
- **Add Model Code**: Include ANN architecture and training steps 🏗️  
- **Preprocessing**: Encode categorical variables (e.g., Geography, Gender) and scale numerical features 📏  
- **Tuning**: Experiment with layer sizes, optimizers, or learning rates ⚙️  
- **Metrics**: Add precision, recall, F1-score, or ROC-AUC 📈  
- **Visuals**: Plot feature distributions, correlation matrices, or loss curves 🎨  
- **Cross-Validation**: Implement k-fold cross-validation for robustness 🔄  

## 🌐 Use Cases
- **Banking**: Identify at-risk customers for targeted retention strategies 🏦  
- **Education**: Learn ANN implementation with TensorFlow 📚  
- **Data Science**: Explore end-to-end ML workflows 🧑‍💻  


