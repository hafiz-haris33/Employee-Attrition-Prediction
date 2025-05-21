# 🧠 Employee Attrition Prediction using IBM HR Analytics

This project builds a classification model to predict whether an employee will leave the company based on HR data. Using data-driven insights, it also proposes HR strategies to reduce attrition and improve retention.

## 📂 Dataset
- **Source**: IBM HR Analytics Employee Attrition & Performance (available on Kaggle)
- Contains demographic, work environment, compensation, and performance data for employees.

## 🧪 Project Workflow

1. **Exploratory Data Analysis (EDA)**  
   - Identify patterns and key factors related to attrition.
   - Visualizations for better understanding.

2. **Model Training**  
   - Used Logistic Regression and Random Forest Classifier.
   - Evaluated with Accuracy, Classification Report, and Confusion Matrix.

3. **Model Interpretability**  
   - Used SHAP (SHapley Additive exPlanations) to explain model predictions.
   - Identified key features influencing attrition.

4. **HR Retention Strategies**  
   - Based on SHAP insights, actionable strategies were proposed to reduce attrition.

## 📊 Key Insights

- **OverTime** is the strongest factor affecting attrition.
- **Younger employees**, **low salary**, and **few stock options** increase attrition risk.
- **Strong manager-employee relationships** help reduce turnover.

## ✅ Recommendations

- Monitor and reduce excessive overtime.
- Provide better compensation and stock options.
- Support career growth for young employees.
- Encourage healthy manager-employee communication.

## 🧰 Tools & Technologies

- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-Learn for model training
- SHAP for model interpretability
- Jupyter/Kaggle Notebooks

## 📁 Folder Structure

Employee-Attrition-Prediction/
- notebook.ipynb # Main notebook
- dataset/ 
- images/ 
- requirements.txt 
- README.md 

## 🚀 How to Run

1. Clone the repository:

   git clone https://github.com/hafiz-haris33/Employee-Attrition-Prediction.git
   cd Employee-Attrition-Prediction

2. Install dependencies:

pip install -r requirements.txt

3. Open and run the notebook:

jupyter notebook notebook.ipynb


🙌 Credits

Dataset: IBM via Kaggle

SHAP: https://github.com/slundberg/shap

