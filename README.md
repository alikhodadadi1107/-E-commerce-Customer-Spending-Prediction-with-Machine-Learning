# E-commerce Customer Spending Prediction with Machine Learning  

## 📌 Project Overview  
This project analyzes **customer behavior data** from an e-commerce company that sells clothing online and provides in-store style consultation.  
The main goal is to determine **whether the mobile app or website contributes more to customer spending** and to build **machine learning models** that predict yearly customer expenditure.  

---

## 📊 Dataset Description  
The dataset contains 8 features:  

- **Customer Info:** Email, Address, Avatar (string fields)  
- **Numerical Features:**  
  - Avg. Session Length  
  - Time on App  
  - Time on Website  
  - Length of Membership  
  - Yearly Amount Spent (Target variable)  

---

## 🛠️ Steps Performed  

### 1. Data Cleaning & Preprocessing  
- Removed duplicates and checked for null values  
- Scaled numerical features using standardization  

### 2. Exploratory Data Analysis (EDA)  
- Distribution of yearly spending  
- Correlation between features and yearly spending  
- Scatter plots to visualize relationships  
- Insights: stronger correlation between *Time on App* and *Yearly Amount Spent*  

### 3. Machine Learning Models  
We trained and evaluated multiple regression models:  
- **Linear Regression**  
- **Ridge Regression**  
- **Lasso Regression**  
- **Decision Tree Regression**  
- **Random Forest Regression**  
- **XGBoost Regression**  

### 4. Model Evaluation  
- Compared models using R² score and Mean Squared Error (MSE)  
- Identified most accurate model for predicting yearly spending  

---

## 📈 Key Insights  
- **Time on App** is a stronger predictor of spending than **Time on Website**  
- **Length of Membership** also has a significant impact on spending  
- Ensemble models (Random Forest, XGBoost) performed better than simple linear models  
- Recommendation: The company should **prioritize improving the mobile app**  

---

## 🛠️ Tools & Libraries  
- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Scikit-learn (Linear, Ridge, Lasso, Decision Tree, Random Forest)  
- XGBoost for gradient boosting  
- Jupyter Notebook for analysis and visualization 
