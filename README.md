# 🧠 Visa Approval Prediction using Machine Learning

This project focuses on building a predictive model to determine the likelihood of visa approval based on candidate and job-related features. The goal is to assist in automating parts of the visa evaluation process by leveraging data-driven insights and machine learning models. Through exploratory data analysis (EDA), feature engineering, and model tuning, this project demonstrates the workflow of developing an end-to-end classification model.

---

## 🎯 Objectives
- Understand key factors influencing visa approvals.
- Perform in-depth univariate and bivariate analysis of applicant and job attributes.
- Apply data preprocessing, feature selection, and model tuning.
- Compare different classification algorithms and evaluate their performance.
- Identify the most significant predictors contributing to visa approval.

---

## 🧩 Key Methods
- **Data Preprocessing:** Handling missing values, encoding categorical variables, and winsorizing outliers.  
- **Exploratory Data Analysis (EDA):** Univariate and bivariate analyses to uncover variable distributions and relationships.  
- **Feature Engineering:** Transformation and selection based on importance scores.  
- **Model Development:** Logistic Regression, Random Forest, and Gradient Boosting (before and after hyperparameter tuning).  
- **Evaluation Metrics:** F1-score, precision, recall, and accuracy.

---

## 📊 Visualizations

| Visualization | Description |
|----------------|-------------|
| ![Univariate Analysis Categorical 1](images/Univariate%20Analysis%20Categorical%201.png) | Distribution of categorical variables affecting visa decisions |
| ![Univariate Analysis Categorical 2](images/Univariate%20Analysis%20Categorical%202.png) | Additional categorical insights |
| ![Univariate Analysis Numerical](images/Univariate%20Analysis%20Numerical.png) | Distribution of numerical variables such as wage and experience |
| ![Bivariate Analysis 1](images/Bivariate%20Analysis%201.png) | Relationship between visa approval and categorical predictors |
| ![Bivariate Analysis 2](images/Bivariate%20Analysis%202.png) | Correlation between wage and visa outcomes |
| ![Wage Analysis](images/Wage%20Analysis.png) | Visualization of prevailing wage across cases |
| ![Boxplot - Prevailing Wage](images/Boxplot%20-%20Prevailing%20Wage.png) | Boxplot highlighting wage distribution and outliers |
| ![Prevailing Wage After Winsorization](images/Prevailing%20Wage%20After%20Winsorization.png) | Wage distribution after winsorization to handle outliers |
| ![Models - Before vs After Tuning](images/Models%20-%20Before%20vs%20After%20Tuning.png) | Comparison of model performance before and after hyperparameter tuning |
| ![Top 10 Feature Importances (Random Forest)](images/Top%2010%20Feature%20Importances%20(Random%20Forest).png) | Key predictors identified by the Random Forest model |
| ![F1 Score Comparison Before vs. After Tuning (Boosting Models)](images/F1%20Score%20Comparison%20Before%20vs.%20After%20Tuning%20(Boosting%20Models).png) | Impact of model tuning on performance metrics |
| ![Top 10 Important Features - Tuned Gradient Boosting](images/Top%2010%20Important%20Features%20-%20Tuned%20Gradient%20Boosting.png) | Final important features influencing visa approval |

---

## 💡 Key Insights & Outcomes

### 🔍 Model Performance & Interpretability
- Achieved the **highest F1 Score (82.06%)**, matching Gradient Boosting but with **easier interpretability**.  
- Handles **class imbalance effectively**.  
- **Reduces overfitting** by aggregating multiple diverse decision trees.  
- **Robust to noise** and **scalable** to high-dimensional data.  
- Offers **faster training** and **easier tuning** than Gradient Boosting.

### ⚙️ Automated Application Screening
- Classifies visa petitions as **likely to be certified or denied**, helping prioritize workload and improve processing efficiency.

### 🚨 Risk Flagging
- Automatically **flags borderline or uncertain cases** for manual verification by legal teams, minimizing decision errors.

### 📈 Transparent, Data-Driven Dashboards
- **Feature importance** visualizations explain the reasons behind predictions, enhancing **trust and transparency** for stakeholders and applicants.

### 🧭 Policy Optimization
- Helps discover patterns (e.g., wage, experience, education) that impact certification rates, **guiding internal policy and strategy decisions**.

---

### 🏆 Final Model Selection
The **Tuned Random Forest Classifier** combines:
- Strong predictive performance  
- Excellent interpretability  
- Speed and scalability  
- Ease of deployment  

💡 **Conclusion:**  
The Tuned Random Forest model proved to be the most **practical and effective solution** for **EasyVisa’s automated visa prediction system**, balancing accuracy, explainability, and operational efficiency.

---

## 🛠️ Technologies Used
- **Python**
- **Pandas**, **NumPy** for data manipulation  
- **Matplotlib**, **Seaborn** for visualization  
- **Scikit-learn** for model building and evaluation  
- **Jupyter Notebook** for analysis workflow

---

## ⚙️ Setup & Installation Instructions
1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/visa-approval-prediction.git
   cd visa-approval-prediction
   
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```
3. Open the Jupyter Notebook:
   ```
   jupyter notebook "Visa Approval Prediction using ML.ipynb"
---

## ▶️ Usage Instructions

- Run each cell in the notebook sequentially to reproduce the analysis.
- Modify parameters (e.g., test size, model hyperparameters) to experiment with model behavior.
- Visualizations are auto-generated during execution for interactive exploration.
---

## 🔗 **Connect with Me**

For feedback, collaboration opportunities, or related queries:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Profile-blue?logo=linkedin)](https://www.linkedin.com/in/indu-r-3a3767170/)

---
