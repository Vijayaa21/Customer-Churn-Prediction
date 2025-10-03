# 📊 Customer Churn Prediction

## 🚀 Project Overview

Customer churn is one of the most pressing challenges for subscription-based businesses like telecom operators, banks, and SaaS companies. Retaining customers is far more cost-effective than acquiring new ones.

This project predicts whether a customer is likely to churn using **machine learning models** on the Telco Customer Churn dataset. It also provides business insights such as key factors influencing churn.

---

## 📂 Dataset

* **Source:** [Kaggle – Telco Customer Churn Dataset](https://www.kaggle.com/blastchar/telco-customer-churn)
* **Rows:** ~7,000 customer records
* **Features:** Customer demographics, services subscribed (phone, internet, streaming), contract type, tenure, monthly charges, and churn label.

---

## 🛠️ Tools & Libraries

* **Python:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
* **ML Model:** Random Forest Classifier
* **Visualization:** Matplotlib & Seaborn
* **Notebook:** Google Colab / Jupyter

---

## 📊 Steps in the Project

1. **Data Cleaning & Preprocessing**

   * Handled missing values in `TotalCharges`
   * Encoded categorical features using Label Encoding
   * Scaled numerical features (Tenure, MonthlyCharges, TotalCharges)

2. **Exploratory Data Analysis (EDA)**

   * Distribution of churn vs non-churn customers
   * Impact of contract type, payment method, and monthly charges on churn
   * Visualized correlations using Seaborn

3. **Feature Engineering**

   * Extracted useful patterns from customer behavior
   * Encoded categorical columns for model compatibility

4. **Model Building**

   * Trained multiple models: Logistic Regression, Random Forest, XGBoost
   * Best performing model: **Random Forest Classifier**

5. **Evaluation**

   * Accuracy: **85%**
   * ROC-AUC: **0.89**
   * Precision, Recall, F1 Score used for better understanding of results
   * Feature importance visualization

---

## 📈 Results & Insights

* Customers on **month-to-month contracts** are **3x more likely** to churn.
* Customers using **electronic checks** as a payment method show the highest churn rates.
* Longer tenure and auto-pay methods significantly reduce churn probability.

---

## 📸 Visualizations

* Churn distribution
* Contract type vs Churn
* Feature importance chart
* Confusion Matrix

---

## ▶️ How to Run This Project

### 🔹 Option 1: Run in Google Colab

1. Open [Google Colab](https://colab.research.google.com/)
2. Upload the notebook file (`Customer_Churn_Prediction.ipynb`)
3. Upload dataset (`WA_Fn-UseC_-Telco-Customer-Churn.csv`)
4. Run all cells

### 🔹 Option 2: Run Locally

```bash
# Clone this repository
git clone https://github.com/your-username/Customer-Churn-Prediction.git

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook Customer_Churn_Prediction.ipynb
```

---

## 📌 Future Improvements

* Deploy interactive dashboard using **Tableau** or **Streamlit**
* Try advanced models like **XGBoost, CatBoost, LightGBM**
* Hyperparameter tuning with GridSearchCV

---

## 👩‍💻 Author

**Vijaya Mishra**


---

⭐ If you like this project, give it a star on GitHub!
