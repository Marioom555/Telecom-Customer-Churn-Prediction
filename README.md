# 📊 Telecom Customer Churn Prediction

## 📌 About the Project  
This project aims to analyze telecom customer data to predict **customer churn** using machine learning techniques. By leveraging customer demographics, subscription details, and usage behavior, the model identifies patterns that influence customer retention.

## 🚀 Features  
- **Data Analysis & Preprocessing** – Cleaning and transforming telecom customer data.
- **Exploratory Data Analysis (EDA)** – Identifying trends and correlations.
- **Feature Engineering** – Creating meaningful features for better predictions.
- **Model Training & Evaluation** – Using machine learning models to predict churn.
- **Performance Metrics** – Evaluating model accuracy with precision, recall, and F1-score.

## 📊 Dataset Overview  
The dataset contains various features related to customer subscriptions, usage, and demographics. Below is a summary:

| Feature | Description |
| --- | --- |
| CustomerID | Unique customer identifier |
| Gender | Customer's gender (Male/Female) |
| SeniorCitizen | Whether the customer is a senior citizen (1/0) |
| Partner | Whether the customer has a partner (Yes/No) |
| Dependents | Whether the customer has dependents (Yes/No) |
| Tenure | Number of months the customer stayed |
| PhoneService | Subscription to phone service (Yes/No) |
| InternetService | Internet provider (DSL/Fiber optic/None) |
| Contract | Type of customer contract (Month-to-month/One year/Two year) |
| PaymentMethod | Customer's payment method |
| Churn | Target variable (Yes/No) |

## 🏗️ Tech Stack  
- **Python** – Data processing and model training.
- **Pandas & NumPy** – Data manipulation and preprocessing.
- **Matplotlib & Seaborn** – Data visualization.
- **Scikit-Learn** – Machine learning modeling.
- **XGBoost & Random Forest** – Advanced predictive modeling.

## 🔧 Setup & Installation  
1. Clone this repository:  
   ```bash
   git clone https://github.com/your-repo/telecom-churn.git
   cd telecom-churn
   ```

2. Create a virtual environment:  
   ```bash
   python -m venv venv
   source venv/bin/activate  # For Mac/Linux
   venv\Scripts\activate  # For Windows
   ```

3. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```
## 📊 Model Visualization & Performance  
###  Customer Demographics
![Image](https://github.com/user-attachments/assets/164da39c-4eed-4ef9-9290-c9f76ef5cfd7)
### Services
![Image](https://github.com/user-attachments/assets/8308c73b-c8bb-4535-b294-85029d5c65d6)

### Tenure and Contract
![Image](https://github.com/user-attachments/assets/01ca92f5-bb0d-41a6-81d2-727e71f5e073)

### Billing and Charges
![Image](https://github.com/user-attachments/assets/dd9c17c4-24d0-4541-bbf8-09210cba4953)
### Churn Count
![Image](https://github.com/user-attachments/assets/fea43255-d820-46f0-8294-1b0efc1bbadb)
### Customer Demogrpahics and Churn

![Image](https://github.com/user-attachments/assets/b8e7f9c6-0f05-4c08-ac0d-b9e7a5b24444)

## 📊 Model Evaluation
The model was evaluated using accuracy, precision, recall, and F1-score to ensure robust churn prediction.
## 1- Confusion Matrix Heatmap
![Image](https://github.com/user-attachments/assets/652088fe-af7e-4aca-9a0c-2bdcdc6bd6d2)
 ## 2- Model Metrix

![Image](https://github.com/user-attachments/assets/71e65e26-98c9-43cc-9d59-04d629037009)
