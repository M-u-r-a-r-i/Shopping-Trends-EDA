# 🛍️ Shopping Trends — Exploratory Data Analysis

An end-to-end Exploratory Data Analysis (EDA) of consumer shopping behavior, built with Python in a Jupyter Notebook. The project uncovers patterns in customer demographics, purchase preferences, seasonal trends, payment habits, and more.

---

## 📁 Repository Structure

```
Shopping-Trends-EDA/
├── EDA.ipynb              # Main analysis notebook
├── shopping_trends.csv    # Dataset
└── .gitignore
```

---

## 📊 Dataset Overview

The dataset (`shopping_trends.csv`) is a synthetic dataset simulating realistic retail customer transactions. It contains **3,900 records** across **18 features**:

| Feature | Description |
|---|---|
| `Customer ID` | Unique identifier per customer |
| `Age` | Customer age (18–70) |
| `Gender` | Male / Female |
| `Item Purchased` | Name of the purchased item |
| `Category` | Product category (Clothing, Accessories, Footwear, Outerwear) |
| `Purchase Amount (USD)` | Transaction value in USD |
| `Location` | US state of purchase |
| `Size` | Item size (S, M, L, XL) |
| `Color` | Item color |
| `Season` | Season of purchase (Spring, Summer, Fall, Winter) |
| `Review Rating` | Customer rating (1–5 stars) |
| `Subscription Status` | Whether the customer is subscribed (Yes/No) |
| `Shipping Type` | Shipping method chosen |
| `Discount Applied` | Whether a discount was applied (Yes/No) |
| `Promo Code Used` | Whether a promo code was used (Yes/No) |
| `Previous Purchases` | Number of prior purchases |
| `Payment Method` | Preferred payment method |
| `Frequency of Purchases` | Purchase frequency (Weekly, Fortnightly, Monthly, etc.) |

---

## 🔍 Analysis Highlights

The notebook walks through a full EDA pipeline:

- **Data Cleaning & Quality Checks** — missing values, data types, duplicates
- **Univariate Analysis** — distribution of age, purchase amounts, ratings, and categorical features
- **Bivariate & Multivariate Analysis** — correlations between demographics, spending habits, and product choices
- **Seasonal Trends** — how purchasing behavior shifts across seasons
- **Customer Segmentation** — behavior differences between subscribers vs. non-subscribers, promo users vs. non-users
- **Payment & Shipping Preferences** — most popular payment methods and shipping types
- **Geographic Insights** — purchase patterns across US locations

---

## 🛠️ Tech Stack

- **Python 3.x**
- **Pandas** — data manipulation
- **NumPy** — numerical operations
- **Matplotlib** — static visualizations
- **Seaborn** — statistical plots
- **Jupyter Notebook** — interactive analysis environment

---

## 🚀 Getting Started

**1. Clone the repository**
```bash
git clone https://github.com/M-u-r-a-r-i/Shopping-Trends-EDA.git
cd Shopping-Trends-EDA
```

**2. Install dependencies**
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

**3. Launch the notebook**
```bash
jupyter notebook EDA.ipynb
```

---

## 📌 Data Source

The dataset is sourced from Kaggle:  
[Customer Shopping Trends Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset) by Sourav Banerjee.

> ⚠️ This is a **synthetic dataset** created for educational purposes. It is not based on real customer data.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
