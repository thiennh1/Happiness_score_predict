# Predicting Happiness Score Based on Lifestyle Habits

## 📌 Project Overview
[cite_start]This project aims to predict individual happiness scores based on daily lifestyle habits using various advanced machine learning models[cite: 8, 10]. [cite_start]Understanding the factors that affect happiness helps individuals make informed decisions to improve their lifestyle and well-being[cite: 8, 22].

## 📊 Dataset
[cite_start]The dataset was collected from Kaggle, containing 24,998 observations representing different individuals[cite: 60, 61]. [cite_start]The target variable is `Happiness_Score`[cite: 63]. 
[cite_start]After correlation analysis, 8 key features were selected for modeling[cite: 153]:
* [cite_start]**Diet Quality** [cite: 153]
* [cite_start]**Mental Health Condition** [cite: 153]
* [cite_start]**Stress Level** [cite: 153]
* [cite_start]**Alcohol Consumption** [cite: 153]
* [cite_start]**Smoking Habit** [cite: 153]
* [cite_start]**Physical Activity Hours** [cite: 153]
* [cite_start]**Sleep Hours** [cite: 153]
* [cite_start]**Work Hours** [cite: 153]

## 🤖 Machine Learning Models
[cite_start]The project evaluates and compares the performance of 7 regression models[cite: 34]:
1. [cite_start]Linear Regression [cite: 34]
2. [cite_start]Lasso Regression [cite: 34]
3. [cite_start]K-Nearest Neighbors (KNN) [cite: 34]
4. [cite_start]Multilayer Perceptron (MLP) [cite: 34]
5. [cite_start]Light Gradient Boosting Machine (LightGBM) [cite: 34]
6. [cite_start]eXtreme Gradient Boosting (XGBoost) [cite: 34]
7. [cite_start]Categorical Boosting (CatBoost) [cite: 34]

## 📈 Key Results
[cite_start]The models were evaluated using MAE, MSE, RMSE, R-squared ($R^2$), and Explained Variance Score[cite: 354]. 
* [cite_start]Advanced boosting algorithms significantly outperformed traditional models[cite: 11].
* [cite_start]**CatBoost** achieved the best performance with an $R^2$ of **0.9438**, meaning it can explain 94.38% of the variance in the Happiness Score[cite: 11, 407].
* [cite_start]**XGBoost** and **LightGBM** followed closely with $R^2$ scores of 0.9426 and 0.9424, respectively[cite: 11, 409].
* [cite_start]**Linear Regression** had the lowest performance ($R^2$ = 0.8309)[cite: 12].

## 💡 Feature Importance & Recommendations
[cite_start]Based on the CatBoost model, the top 3 lifestyle factors that most significantly impact the happiness score are[cite: 496, 497, 454, 459]:
1. [cite_start]**Work Hours**: Establishing a boundary between work and rest is crucial[cite: 497, 498].
2. [cite_start]**Physical Activity Hours**: Maintaining regular exercise habits greatly improves well-being[cite: 454, 456].
3. [cite_start]**Mental Health Condition**: Equipping oneself with emotional first-aid skills and seeking professional help when needed is highly recommended[cite: 459, 462, 463].

## 👥 Authors
* [cite_start]Duong Quoc Anh [cite: 2]
* [cite_start]Nguyen Huu Thien [cite: 25]
* [cite_start]Phan Thi Tuong Vi [cite: 4]
* [cite_start]Le Thi Anh Xuan [cite: 27]
[cite_start]*(University of Information Technology)* [cite: 3, 5, 26, 28]
