# AI Diet Planner – Calorie Prediction Model

An AI-powered diet planning tool that predicts **daily calorie intake** using personal health details such as weight, height, age, gender, disease type, and physical activity level. The project uses a **Random Forest model** and a **Gradio web interface**.

---

## 🚀 Features
- Predicts daily calorie requirement  
- Calculates BMI and gives health tips  
- Preprocessing with pipelines  
- Handles numeric & categorical data  
- Interactive Gradio UI  
- Saves trained model using Joblib  
- Feature importance visualization  

---

## 📊 Technologies Used
- Python  
- Scikit-learn  
- Pandas, NumPy  
- RandomForestRegressor  
- Gradio  
- Matplotlib  
- Joblib  

---

## 🧠 Workflow

### 1. Load dataset  
### 2. Preprocess  
- Numeric → Imputation + Scaling  
- Categorical → Imputation + One-Hot Encoding  

### 3. Train Model  
RandomForestRegressor is used as the prediction model.

### 4. Evaluate  
Metrics used:
- MAE  
- RMSE  
- R² Score  

### 5. Gradio Web App  
Inputs:
- Weight  
- Height  
- Age  
- Gender  
- Disease Type  
- Activity Level  

Outputs:
- Predicted Calorie Intake  
- BMI  
- Health Advice
