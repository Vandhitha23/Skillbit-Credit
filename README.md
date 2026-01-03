# 💳 Credit Risk Assessment using Machine Learning

## 📌 Project Overview
This project implements a machine learning classification model to assess the **credit risk of loan applicants** based on their financial history and other relevant factors.  
The model predicts whether an applicant belongs to one of the following classes:

- Low Risk (Good Credit)
- High Risk (Bad Credit)

The classification is performed using the **Logistic Regression** algorithm.

## 📊 Dataset
The dataset used in this project is **german_credit_data.csv**, which contains historical data of loan applicants.  
Each sample has the following features:

- Age  
- Job  
- Housing  
- Saving accounts  
- Checking account  
- Credit amount  
- Duration  
- Purpose  
- Credit Risk (target label)

## ⚙️ Technologies Used
- Python  
- Pandas  
- Scikit-learn  

## 🧠 Machine Learning Workflow
1. Load the dataset from a CSV file  
2. Handle missing values  
3. Encode categorical variables  
4. Split the dataset into training and testing sets  
5. Scale numerical features  
6. Train a Logistic Regression classifier  
7. Evaluate the model using accuracy and classification metrics  
8. Predict credit risk for new loan applicants  

## 📈 Model Performance
The trained model achieved the following results on the test dataset:

- Accuracy: 76%  
- Precision: 0.75  
- Recall: 0.76  
- F1-score: 0.75  

These results indicate realistic performance for a real-world credit risk assessment problem.

## 🔮 Example Prediction
**Input values:**
- Age: 30  
- Credit Amount: 5000  
- Duration: 24 months  
- Saving Account: Moderate  
- Checking Account: Low  

**Output:**
- Credit Risk: **Good (Loan Approved)**

## 📂 Project Structure
```text
├── german_credit_data.csv
├── credit_risk_assessment.py
└── README.md

✅ Conclusion
This project demonstrates how classification algorithms can be used to assess credit risk using historical financial data.
It highlights real-world challenges such as identifying high-risk applicants while maintaining acceptable approval accuracy.

👤 Author
Vandhitha
Entry-Level AI & Machine Learning Enthusiast
