# 🩺 Diabetes Prediction System  

## 📊 Project Overview  
This project aims to build predictive models for diabetes risk using **national health survey data**. The goal is to aid early diagnosis and risk mitigation by predicting the likelihood of diabetes based on various health-related features.

The models were developed using **Multinomial Logistic Regression** and **Decision Trees**, both enhanced with **SMOTE** (Synthetic Minority Over-sampling Technique) to handle class imbalance in the dataset. An **interactive frontend** was built using **Streamlit**, allowing users to input data and visualize predictions in real-time. The system offers actionable insights for individuals and healthcare professionals to better understand the factors contributing to diabetes risk.

---

## ⚙️ Features  

### 🔬 Predictive Models  
- **Multinomial Logistic Regression**: Used for predicting the probabilities of different diabetes risk categories based on input features.  
- **Decision Trees**: Utilized for creating an interpretable model that visually displays how decisions are made based on feature thresholds.  
- **SMOTE (Synthetic Minority Over-sampling Technique)**: Applied to address the imbalance in the dataset, ensuring fair training of the models and improving prediction accuracy.  

### 🌐 Streamlit Interactive Frontend  
- **User Input Interface**: Allows users to input their health data (age, BMI, blood pressure, etc.) for prediction.  
- **Visualization**: Displays the predicted risk and relevant data visualizations, such as probability distributions and feature importance charts.  
- **Real-Time Feedback**: Based on input data, the model predicts the risk of diabetes and shows actionable insights for risk mitigation.  

---

## 🛠️ Tools and Libraries  

### **Python**  
The project was implemented using **Python** for data processing, model training, and frontend development.  

### **Libraries Used**  
- **Scikit-learn**: For implementing the Multinomial Logistic Regression and Decision Tree models.  
- **SMOTE**: From the **imbalanced-learn** library to balance the dataset by generating synthetic data points.  
- **Streamlit**: Used for building the interactive frontend, enabling real-time user input and visualization of predictions.  
- **Matplotlib & Seaborn**: For generating visualizations to enhance understanding of model predictions and data insights.  
- **Pandas**: For data manipulation and analysis.  
- **NumPy**: For numerical operations and feature engineering.  

---

## 📈 Model Performance  

### **Evaluation Metrics**  
The models were evaluated using metrics such as **accuracy**, **precision**, **recall**, and **F1-score** to assess their performance in predicting diabetes risk. The **confusion matrix** and **classification report** are used to measure how well the models perform across different classes.  

### **Model Comparison**  
- The **Decision Tree** model provides high interpretability, showing clear decision paths.  
- The **Multinomial Logistic Regression** model offers probabilistic outputs and works well for multi-class classification.  

---
