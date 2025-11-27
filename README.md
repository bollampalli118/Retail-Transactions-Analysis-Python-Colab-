# Retail Transactions Analysis (Python / Colab)
![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Project-Active-success)
![Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange)
This project explores a synthetic **retail transactions dataset** using Python.  
It walks through a typical data analytics workflow:

1. Data loading & cleaning  
2. Feature engineering (date-based fields)  
3. Exploratory data analysis (EDA)  
4. Customer behavior analysis  
5. Promotion & discount impact  
6. Seasonality & revenue trends  
7. Visual dashboards with plots

The notebook is written for **Google Colab**, but can also be run locally.

---

## 🧾 Dataset

**File:** `Retail_Transactions_Dataset.csv`  
📌 Note: Dataset not included in repository due to size limit (161MB).
Dataset Download: Google Drive Link: <https://drive.google.com/file/d/1EszFXdUFNXa7etw_5VquoSIWENeZlEg_/view?usp=sharing>


**Columns (main):**

- `Transaction_ID` – Unique ID for each transaction  
- `Date` – Timestamp of the transaction  
- `Customer_Name` – Name of the customer  
- `Product` – List of products purchased in that transaction  
- `Total_Items` – Total number of items in the basket  
- `Total_Cost` – Total value of the transaction  
- `Payment_Method` – Payment used (Cash, Credit Card, Debit Card, Mobile Payment)  
- `City` – City where transaction occurred  
- `Store_Type` – Type of store (Supermarket, Pharmacy, Specialty Store, etc.)  
- `Discount_Applied` – Whether a discount was applied (True/False)  
- `Customer_Category` – Segment (Professional, Homemaker, Student, etc.)  
- `Season` – Season of the transaction (Winter, Spring, Summer, Fall)  
- `Promotion` – Promotion type (BOGO, Discount on Selected Items, No Promotion)

New columns engineered in the code:

- `Year` – Year extracted from `Date`  
- `Month` – Month extracted from `Date`  
- `DayOfWeek` – Day name extracted from `Date` (Monday, Tuesday, …)

---

## 🛠️ Tech Stack & Libraries

The analysis uses:

- **pandas** – data manipulation  
- **numpy** – numerical operations  
- **matplotlib** & **seaborn** – static visualizations  
- **plotly.express** – interactive visualizations (optional)  
- **scipy.stats** – statistical tools (imported for potential use)  
- **sklearn.preprocessing.StandardScaler**, **sklearn.cluster.KMeans** – for potential advanced analysis (clustering), currently imported but not deeply used in this version

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/184ZgzixEHimoeslxcrRz0wU3UAZjMEre)
