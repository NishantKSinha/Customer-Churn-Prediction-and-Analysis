
# 📊 Customer Churn Prediction Using Machine Learning

A machine learning project that predicts customer churn using classification algorithms such as KNN, SVC, Logistic Regression, Decision Tree, and Random Forest. Includes data analysis, preprocessing, visualization, model comparison, and a  prediction interface with saved models.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📝 Overview

Customer churn refers to the phenomenon of customers leaving a service provider. In the banking industry, retaining customers is crucial. This project builds a predictive system using machine learning to identify customers at risk of churning based on various attributes.

I used multiple supervised ML algorithms, compared their performance, and developed an interactive script that lets users predict churn using their selected model.

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## ✨ Project Features

- Load and analyze real-world customer churn dataset
  
- Clean and preprocess data using encoding and scaling
  
- Perform Exploratory Data Analysis (EDA) with visualizations
  
- Train and evaluate multiple ML classification models
  
- Compare model accuracy in a clear tabular form
  
- Save and load trained models for future predictions
  
- Interactive CLI-based prediction system for new customer data
  
- Label-encoded input system to support prediction on unseen data

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📌 Dataset Features

- **Source**: [Kaggle - Customer Churn Prediction Dataset](https://www.kaggle.com/code/muqaddasejaz/customer-churn-prediction)

The dataset contains customer details and whether they exited (churned) or not.

| Feature            | Description                          |
|--------------------|--------------------------------------|
| CreditScore        | Customer's credit score              |
| Geography          | Country: 0 = France, 1 = Germany, 2 = Spain |
| Gender             | Gender: 0 = Female, 1 = Male         |
| Age                | Customer's age                       |
| Tenure             | Number of years with the bank        |
| Balance            | Bank account balance                 |
| NumOfProducts      | Number of products customer uses     |
| HasCrCard          | Does the customer have a credit card |
| IsActiveMember     | Activity status in bank              |
| EstimatedSalary    | Estimated salary                     |
| Exited             | Target label (0 = No churn, 1 = Churn) |

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Tools & Technologies Used

- **Python**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn** (ML models, preprocessing, evaluation)
- **Pickle** (for model saving/loading)

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 🤖 Machine Learning Models & Accuracy Comparison

| Machine Learning Model        | Accuracy |
|------------------------------|----------|
| K-Nearest Neighbors (KNN)    | 78%      |
| Support Vector Classifier    | 79%      |
| Logistic Regression          | 86%      |
| Decision Tree Classifier     | 86%      |
| Random Forest Classifier     | 86%      |

----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📈 Project Workflow


1. Import Required Libraries
2. Load Dataset (CSV file)
3. Perform Data Analysis
4. Data Preprocessing and Label Encoding
5. Data Visualization using Seaborn & Matplotlib
6. Train Machine Learning Models (5 models)
7. Evaluate Models and Compare Accuracy
8. Save Best Models using Pickle
9. CLI-based Prediction: Choose Model and Input Customer Data

    -----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

 ##  ✅ Results
 
- Highest Accuracy (86%) was achieved using Logistic Regression, Decision Tree, and Random Forest models.

- The system allows real-time predictions based on user input.

- Data visualization helped in understanding churn trends and feature correlations.

- The code is modular and reusable, making it easy to scale or improve further.

- All trained models are saved and can be loaded anytime for prediction.

-  Data Visualization:
    
- Churm distribution with respect to Gender

 <img width="580" height="455" alt="gender" src="https://github.com/user-attachments/assets/3206daa1-019a-40e2-bbdf-513239520de4" />

- Churm distribution with respect to Tenure

 <img width="850" height="547" alt="tenure" src="https://github.com/user-attachments/assets/4fcd37c2-e709-464d-af3f-cb8be118d721" />

- Churm distribution with respect to Age

 <img width="846" height="547" alt="age" src="https://github.com/user-attachments/assets/3d441d76-c21f-4898-abf3-a3255350928f" />


-  **Evaluation Metrics**:
  
  - Confusion Matrix
  - KNN:

  <img width="435" height="298" alt="knn" src="https://github.com/user-attachments/assets/a0e4aeec-9556-4afb-b044-b53540e6f5f1" />

 - SVC:
 
  <img width="363" height="298" alt="svc" src="https://github.com/user-attachments/assets/7a656f06-91a4-4b66-89fc-f9180cff96af" />

 - Random Forest:
 
  <img width="390" height="298" alt="rf" src="https://github.com/user-attachments/assets/ec42c470-f0f7-4083-a2f5-8626a709d34a" />

- Decision Tree:

  <img width="382" height="298" alt="dt" src="https://github.com/user-attachments/assets/21ef3367-d968-4216-80ab-d025cc6eb321" />

- Logistic Regression:

  <img width="410" height="298" alt="lr" src="https://github.com/user-attachments/assets/4b304bf7-f941-4b33-84fb-782f1d9e7a43" />

- Prediction on new data:

  <img width="768" height="423" alt="predictions" src="https://github.com/user-attachments/assets/8425ef1d-c3c6-40b9-986e-db1bd45b6ab2" />


  <img width="788" height="481" alt="prediction" src="https://github.com/user-attachments/assets/5e79320b-ce50-4a5c-8591-9a973eef1a38" />


- ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


## 📚 References

- https://www.avaus.com/blog/predicting-customer-churn/

- https://medium.com/@allanouko17/customer-churn-prediction-using-machine-learning-ddf4cd7c9fd4
  
- https://www.analyticsvidhya.com/blog/2022/09/bank-customer-churn-prediction-using-machine-learning/
   

----------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 👩‍💻 Author

Muqadas Ejaz

BS Computer Science (AI Specialization)

Machine Learning & Computer Vision Enthusiast

📫 Connect with me on [LinkedIn](https://www.linkedin.com/in/muqadasejaz/)  

🌐 GitHub: [github.com/muqadasejaz](https://github.com/muqadasejaz)

------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## 📎 License

This project is open-source and available under the [MIT License](LICENSE).
