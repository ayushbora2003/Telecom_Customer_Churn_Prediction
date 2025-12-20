# Telecom Customer Churn Prediction

## 📋 Project Overview
This project predicts customer churn for a telecom company using machine learning. The goal is to identify customers at high risk of leaving, allowing the company to take proactive retention measures.

## 🎯 Business Problem
Customer churn is costly for telecom companies. By predicting which customers are likely to leave, the company can implement targeted retention strategies, saving revenue and improving customer satisfaction.

## 📊 Dataset
- **Source**: Telecom customer data
- **Records**: 7,043 customers
- **Features**: 20 features including demographics, services used, and billing information
- **Target**: Churn (Yes/No)

## 🔧 Technologies Used
- Python 3.x
- Pandas & NumPy (Data manipulation)
- Matplotlib & Seaborn (Visualization)
- Scikit-learn (Machine learning)
- Jupyter Notebook

## 📈 Key Results
- **Best Model**: Logistic Regression
- **Accuracy**: 80.3%
- **Precision**: 64.7%
- **Recall**: 56.5%
- **F1-Score**: 60.4%

## 🚀 How to Run
1. Clone the repository
2. Install requirements: `pip install -r requirements.txt`
3. Run the Jupyter notebook: `jupyter notebook churn_prediction.ipynb`

## 📁 Project Structure
telecom-churn-prediction/
├── churn_prediction.ipynb # Main notebook

    ├──images/ # Generated visualizations

    ├──data/data_file.csv # Dataset

    ├───model/churn_prediction_model.pkl # Saved model

├── requirements.txt # Dependencies

└── README.md
