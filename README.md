# 📊 Profit Prediction of a Company using Machine Learning
*A Machine Learning Project for Predicting Company Profit Based on Expenditure Patterns* 

## 👥 Team Members & Student IDs

- **M. Thanmayee** — *700776997*
- **D. Sri Kathyayini** — *700769996*
- **Himaja Arabati** — *700772489*
- **Hemalatha Mareedu** — *700771973*
- **K. Lakshmi Prasanna** — *700772585*



## 📘 Project Overview
This project develops a machine learning model to predict company profit based on financial expenditures such as:
- R&D Spend  
- Administration Cost  
- Marketing Spend  
- State (categorical feature)

The project follows a complete ML pipeline including preprocessing, EDA, model training, evaluation, and business insights.

## 🎯 Objectives
- Analyze how different expenditures affect company profit.
- Identify which features contribute most to profitability.
- Train and compare multiple regression models.
- Evaluate model performance using R², RMSE, MAE, and cross-validation.
- Recommend the best model for real-world prediction.

## 🏗️ Project Workflow / Architecture
1. **Data Acquisition**  
2. **Data Preprocessing**  
   - Missing value check  
   - One-hot encoding (State)  
   - Feature scaling  
   - Multicollinearity analysis (VIF)  
3. **Exploratory Data Analysis (EDA)**  
   - Correlation matrix  
   - Heatmaps & pairplots  
   - Outlier analysis  
4. **Feature Engineering**  
5. **Model Development**  
   - Linear Regression  
   - Ridge Regression  
   - Lasso Regression  
   - Random Forest Regression  
6. **Model Evaluation**  
7. **Selection of Best Model**  
8. **Prediction & Business Insight Generation**


## 📂 Dataset
The dataset used is the **50_Startups** dataset containing:
- R&D Spend  
- Administration  
- Marketing Spend  
- State  
- Profit (target variable)

## 🔧 Tools & Technologies

### Programming
- **Python**

### Libraries
- NumPy, Pandas  
- Matplotlib, Seaborn  
- Scikit-learn

### Development Environment
- **Jupyter Notebook**

## 🧠 Machine Learning Models Used
Four supervised regression algorithms were trained:

1. **Linear Regression** – Baseline model  
2. **Ridge Regression** – L2 regularization  
3. **Lasso Regression** – L1 regularization  
4. **Random Forest Regression** – Best-performing ensemble model  

## 📈 Model Evaluation

### Metrics Used
- R² Score  
- RMSE  
- MAE  
- Cross-validation Score  

### Performance Summary
| Model | R² Score |
|-------|----------|
| **Random Forest** | ≈ 0.905 |
| Linear Regression | ≈ 0.900 |
| Lasso Regression | ≈ 0.900 |
| Ridge Regression | ≈ 0.896 |

Random Forest achieved:
- Lowest RMSE  
- Lowest MAE  
- Best generalization

  <img width="733" height="451" alt="image" src="https://github.com/user-attachments/assets/26865555-447e-4d78-9c63-124087061a91" />


## 🏆 Best Model & Key Insights

### ⭐ Best Model: **Random Forest Regressor**
Reasons:
- Captures nonlinear patterns  
- Handles correlated features effectively  
- Reduces overfitting  

### 🔍 Feature Importance Ranking
1. **R&D Spend** – strongest driver of profit  
2. **Marketing Spend** – moderate effect  
3. **Administration Cost** – weak influence  

## 📊 Results & Discussion
- All four regression models performed well.  
- Random Forest achieved the highest accuracy and stability.  
- R&D spending shows the strongest correlation with profit.  
- Marketing spend provides additional value, while administration cost contributes least.  
- The dataset’s small size (50 rows) limits generalization, but insights remain meaningful.  

## 🚀 Conclusion
This project successfully builds and evaluates machine learning models for predicting company profit.  
Key conclusions:
- **Random Forest is the most effective model** for this dataset.  
- **R&D spending is the most influential factor** in determining profitability.  
- Machine learning provides valuable support for business budgeting and investment decisions.
<img width="631" height="393" alt="image" src="https://github.com/user-attachments/assets/82af1d03-4e24-491d-b5a8-dc18ee1f8b4a" />


## 🔮 Future Work
- Use larger datasets with more diverse features  
- Incorporate economic and market-related variables  
- Explore advanced models (XGBoost, CatBoost, Neural Networks)  
- Deploy as a real-time prediction system  





