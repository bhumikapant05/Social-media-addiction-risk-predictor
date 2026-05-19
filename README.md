# Social-media-addiction-risk-predictor
Machine Learning model to predict social media addiction risk using different learning approaches like Random Forest, SVM, and Logistic Regression with SHAP explanations.

## Project Overview

This model analyzes 8 key behavioral features to classify users into addiction risk categories:
- Daily screen time hours
- Social media usage hours  
- Gaming hours
- Work/study hours
- Sleep hours
- Notifications per day
- App opens per day
- Weekend screen time

## Models Implemented

1. **Logistic Regression** - Linear baseline model
2. **Support Vector Machine (SVM)** - Non-linear classification with RBF kernel
3. **Random Forest** - Ensemble method (best performance)

## Key Features

- **SHAP Explanations**: Understand which features drive each prediction
- **Multi-Model Consensus**: Compare predictions across all three algorithms
- **Risk Score Visualization**: Interactive probability breakdowns
- **Preventive Insights**: Personalized recommendations based on risk patterns

## Results

- **Random Forest Accuracy**: 90%
- **SVM Accuracy**: 94%
- **Logistic Regression Accuracy**: 93%

## Technologies Used

- Python 3
- scikit-learn
- pandas, numpy
- matplotlib, seaborn
- SHAP

## Dataset

- **Source**: Smartphone Usage and Addiction Analysis Dataset
- **Size**: 7,500 rows
- **Features**: 8 behavioral metrics

## 🚀 How to Run

1. Clone this repository
2. Install dependencies: `pip install pandas numpy scikit-learn matplotlib seaborn shap`
3. Run the notebook/script
4. Input your usage patterns when prompted

## 👤 Author

[Your Name]  
[Your University/Course - Optional]

## 📄 License

This project is for educational purposes.
