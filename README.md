# 🧠 Parkinson's Disease Prediction using Machine Learning

## 📌 Project Overview  
This project focuses on predicting **Parkinson's Disease** using machine learning techniques.  
Parkinson’s disease is a progressive disorder of the nervous system that affects movement.  
Early detection can play a crucial role in providing timely medical assistance and improving quality of life.  

The model analyzes biomedical voice measurements to classify whether a patient has Parkinson's disease or not.

---

## 📂 Dataset  
- **Source**: UCI Machine Learning Repository – Parkinson’s Disease dataset  
- **Attributes**: 24 biomedical voice measurements  
- **Target Variable**:  
  - `1` → Parkinson’s Disease Present  
  - `0` → Healthy  

---

## ⚙️ Project Workflow  

1. **Data Collection**  
   - Used Parkinson’s dataset containing patient voice features.  

2. **Exploratory Data Analysis (EDA)**  
   - Checked null values and missing data.  
   - Visualized feature distributions.  
   - Correlation analysis of variables.  

3. **Data Preprocessing**  
   - Standardization of features using `StandardScaler`.  
   - Splitting dataset into **training** and **testing sets**.  

4. **Model Training**  
   - Implemented multiple ML algorithms:  
     - Logistic Regression  
     - Random Forest Classifier  
     - Support Vector Machine (SVM)  
     - Gradient Boosting  
   - Hyperparameter tuning for better performance.  

5. **Model Evaluation**  
   - Metrics: Accuracy, Precision, Recall, F1-Score  
   - Confusion Matrix & ROC Curve  

---

## 📊 Results  
- Best performing model achieved **high accuracy in predicting Parkinson’s Disease**.  
- Performance comparison across models was visualized for better understanding.  

---

## 🛠️ Technologies Used  
- **Python**  
- **Libraries**:  
  - `numpy`, `pandas` → Data handling  
  - `matplotlib`, `seaborn` → Visualization  
  - `scikit-learn` → ML models and evaluation  

---

## 🚀 How to Run the Project  

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/parkinson-disease-prediction.git
2. Navigate to project folder:
   ```bash
   pip install -r requirements.txt
4. Run the Jupyter Notebook:
  ```bash
  jupyter notebook Parkinson_Disease_Prediction.ipynb
```

📌 Business Value

Supports early detection of Parkinson’s disease.
Assists healthcare professionals with a decision-support system.
Can be extended into a real-time diagnostic tool.
