# Bank Customer Churn Analysis 🚀💳

## What are we doing here? 🤔

In this project, we analyze a dataset of bank credit card customers to understand customer churn (i.e., when customers leave the bank). We explore customer demographics, account information, and transaction behavior to predict whether a customer will close their account or stay.

---

## Dataset Overview 📊

- The dataset contains **10,127** customers with **21 features** (columns).
- Attributes include customer age, gender, income category, card type, credit limit, transaction amounts, and more.
- The target variable is **Attrition_Flag** which shows if a customer is an active or churned customer.

---

## Main Steps of the Project 🛠️

1. **Import Libraries**  
   We use popular Python libraries like `pandas`, `numpy`, `sklearn`, `matplotlib`, and `seaborn`.

2. **Load Dataset**  
   Data is loaded from a CSV file `BankChurners.csv` and cleaned by dropping unnecessary columns.

3. **Explore the Data**  
   We check the dataset shape, data types, missing values, and summary statistics.  
   Visualize distributions and correlations using histograms and heatmaps.

4. **Preprocessing**  
   - Drop irrelevant columns (e.g., `CLIENTNUM`).  
   - Encode categorical variables using Label Encoding and One-Hot Encoding.

5. **Data Visualization**  
   - Histograms for numerical data to understand distributions.  
   - Correlation heatmap to identify relationships between variables.  
   - Count plot for class balance of the target variable.

6. **Prepare for Modeling**  
   The dataset is now clean and ready for applying machine learning models to predict customer churn.

---

## Why this matters? 🌟

Understanding customer churn helps banks improve customer retention strategies, tailor offers, and reduce losses. Using ML models on such data can predict churn early and help banks act proactively.

---

Happy analyzing! 📈💡