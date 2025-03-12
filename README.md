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

## 📊 Model Performance  
The model was evaluated using accuracy, precision, recall, and F1-score to ensure robust churn prediction.
