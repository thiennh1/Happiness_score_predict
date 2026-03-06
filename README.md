# Predicting Happiness Score Based on Lifestyle Habits

## 📌 Project Overview
This project aims to predict individual happiness scores based on daily lifestyle habits using various advanced machine learning models. Understanding the factors that affect happiness helps individuals make informed decisions to improve their lifestyle and well-being.

## 📊 Dataset
The dataset was collected from Kaggle, containing 24,998 observations representing different individuals. The target variable is `Happiness_Score`. 
After correlation analysis, 8 key features were selected for modeling:
* **Diet Quality** 
* **Mental Health Condition** 
* **Stress Level** 
* **Alcohol Consumption** 
* **Smoking Habit** 
* **Physical Activity Hours** 
* **Sleep Hours** 
* **Work Hours**

<img width="1359" height="1223" alt="image" src="https://github.com/user-attachments/assets/93056b7a-0b08-4089-854f-1f1afd191a3c" />

## 🤖 Machine Learning Models
The project evaluates and compares the performance of 7 regression models:
1. Linear Regression 
2. Lasso Regression 
3. K-Nearest Neighbors (KNN) 
4. Multilayer Perceptron (MLP) 
5. Light Gradient Boosting Machine (LightGBM) 
6. eXtreme Gradient Boosting (XGBoost) 
7. Categorical Boosting (CatBoost) 

## 📈 Key Results
The models were evaluated using MAE, MSE, RMSE, R-squared ($R^2$), and Explained Variance Score. 
* Advanced boosting algorithms significantly outperformed traditional models.
* **CatBoost** achieved the best performance with an $R^2$ of **0.9438**, meaning it can explain 94.38% of the variance in the Happiness Score.
* **XGBoost** and **LightGBM** followed closely with $R^2$ scores of 0.9426 and 0.9424, respectively.
* **Linear Regression** had the lowest performance ($R^2$ = 0.8309).

## 💡 Feature Importance & Recommendations
Based on the CatBoost model, the top 3 lifestyle factors that most significantly impact the happiness score are:
1. **Work Hours**: Establishing a boundary between work and rest is crucial.
2. **Physical Activity Hours**: Maintaining regular exercise habits greatly improves well-being.
3. **Mental Health Condition**: Equipping oneself with emotional first-aid skills and seeking professional help when needed is highly recommended.

<img width="975" height="644" alt="image" src="https://github.com/user-attachments/assets/46806f5e-a529-430c-b757-d7a696a572ec" />

## 👥 Authors
* Duong Quoc Anh *(University of Information Technology)*  
* Nguyen Huu Thien *(University of Information Technology)* 
* Phan Thi Tuong Vi *(University of Information Technology)* 
* Le Thi Anh Xuan *(University of Information Technology)* 
