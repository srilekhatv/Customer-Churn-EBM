# Customer Churn Classification with Explainable AI

## 📌 Overview
This project focuses on building interpretable machine learning models to predict customer churn. The main objective is not just to predict churn accurately but to deeply understand the *why* behind each prediction using feature importance analysis and the Explainable Boosting Machine (EBM).

## 📊 Dataset
The dataset used is `Customer Churn.csv`, containing customer demographics, service usage patterns, contract types, and churn labels. It’s a classic binary classification problem aimed at identifying customers who are likely to leave.

## 🎯 Objectives
- Predict customer churn using machine learning classification models.
- Analyze **feature importances** to understand which factors drive churn.
- Apply the **Explainable Boosting Machine (EBM)** to gain both global and local interpretability.
- Compare explainability between traditional and interpretable models.

## 🛠️ Technologies & Libraries
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- InterpretML (EBM)
- Statsmodels

## ⚙️ How to Run
1. Clone this repository.
2. Install the required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn interpret statsmodels
   ```
3. Place `Customer Churn.csv` in the project directory.
4. Open and run the notebook `Homework 1 - Classification Task_Srilekha.ipynb` using Jupyter or Google Colab.

## 🤖 Models Used
- **Random Forest Classifier**: For performance baseline and feature importance evaluation.
- **Explainable Boosting Machine (EBM)**: For interpretable modeling and in-depth explanation of predictions.

## 🔍 Explainability & Insights
- **Feature Importance (Random Forest)**: Showed which variables (like tenure, contract type, monthly charges) most influenced churn.
- **Global Interpretability (EBM)**: Visualizations show how features like “tenure” or “InternetService” affect churn probabilities.
- **Local Interpretability (EBM)**: For individual predictions, we can trace exactly which features pushed a customer toward churn or retention.

## 📈 Results
- Random Forest achieved solid performance and highlighted key churn drivers.
- EBM produced comparable results while enhancing trust and transparency.
- The combined approach helped uncover actionable business insights.

## 📌 Conclusion
This project emphasizes that accurate machine learning predictions and explainability can go hand in hand. By using EBM and feature importance analysis, we bridge the gap between data science and real-world decision-making.

## 👩‍💻 Author
**Srilekha Tirumala Vinjamoori**  
[LinkedIn](https://www.linkedin.com/in/srilekha-tirumala-vinjamoori/) | [GitHub](https://github.com/srilekhatv)