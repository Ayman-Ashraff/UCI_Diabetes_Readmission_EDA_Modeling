# 🏥 Healthcare Readmission Prediction

## 📌 Project Overview
Predicting 30-day hospital readmission for diabetic patients using the UCI 
Diabetes Dataset (1997-2008) containing 100,000+ patient records.

## 🎯 Problem Statement
Hospital readmissions within 30 days cost the US healthcare system 
billions annually. This project builds a machine learning model to 
identify high-risk patients BEFORE they are discharged.

## 📊 Dataset
- **Source:** UCI Machine Learning Repository
- **Size:** 101,766 patient records
- **Features:** 50 features (demographic, clinical, medication)
- **Target:** Binary readmission within 30 days

## 🛠️ Tech Stack
- **Python** (Pandas, NumPy, Scikit-learn)
- **Visualization** (Matplotlib, Seaborn)
- **Models** (Logistic Regression, Random Forest)

## 📈 Results
| Model | Accuracy | ROC AUC | Recall |
|-------|----------|---------|--------|
| Logistic Regression | 66.99% | 0.6426 | 50.77% |
| Random Forest | ~68% | ~0.67 | ~52% |

## 💰 Business Impact
- Model identifies **60%+** of at-risk patients
- Estimated **$3.9M+ net savings** per year
- Enables targeted interventions by risk category

## 🔍 Project Structure
├── healthcare_readmission.ipynb  # Main analysis notebook
├── cleaned_diabetic_data.csv     # Processed dataset
└── visualizations/               # All generated charts

## 📋 Key Steps
1. Data Quality Assessment
2. Data Cleaning & Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Model Training & Evaluation
6. Business Impact Analysis
7. Risk Stratification

## 🚀 How to Run
1. Clone this repository
2. Install requirements: `pip install pandas numpy scikit-learn matplotlib seaborn`
3. Open `healthcare_readmission.ipynb` in Jupyter/Colab
4. Run all cells!

## 👤 Author
**Your Name**
- LinkedIn: https://www.linkedin.com/in/aymanashraff
- GitHub: https://github.com/Ayman-Ashraff
