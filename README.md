# 📊 Week 1 Mini Project - Brazilian E-Commerce Data Analysis

## 📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on the Brazilian Olist E-Commerce Dataset. The objective is to clean and analyze customer orders, payments, products, and delivery information to uncover valuable business insights and trends.

The project demonstrates practical usage of Python data analysis libraries such as Pandas, NumPy, Matplotlib, and Seaborn.

---

## 🎯 Objectives

- Merge multiple e-commerce datasets into a single analytical dataset.
- Perform data cleaning and preprocessing.
- Handle missing values and duplicate records.
- Explore customer purchasing behavior.
- Analyze revenue generation across states.
- Study payment patterns and order statuses.
- Visualize trends using different chart types.
- Generate insights useful for business decision-making.

---

## 🗂 Dataset Used

**Brazilian E-Commerce Public Dataset by Olist**

The analysis combines information from:

- Customers Dataset
- Orders Dataset
- Order Items Dataset
- Payments Dataset
- Products Dataset

### Key Features

- Customer Location
- Order Status
- Product Price
- Freight Charges
- Payment Type
- Payment Installments
- Product Information
- Purchase Timestamps

---

## 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Operations |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Jupyter Notebook | Development Environment |

---

## 📂 Project Workflow

### 1. Data Loading

Imported datasets using Pandas:

```python
pd.read_csv()
```

Merged datasets using:

```python
merge()
```

---

### 2. Data Cleaning

Performed:

- Missing Value Detection
- Duplicate Removal
- Median Imputation for Numerical Columns
- "Unknown" Filling for Categorical Columns

```python
df.drop_duplicates()
df.fillna()
```

---

### 3. Data Exploration

Analyzed:

- Dataset Shape
- Columns
- Datatypes
- Statistical Summary
- Correlation Analysis

Methods Used:

```python
df.info()
df.describe()
df.corr()
```

---

### 4. Data Filtering & Selection

Used:

```python
loc[]
iloc[]
query()
```

Examples:

- High-price products
- Delivered orders
- Orders with price > 100

---

### 5. Aggregation & Grouping

Business insights generated through:

```python
groupby()
agg()
```

Metrics:

- Revenue by State
- Sales by Product Category
- Average Product Price
- Order Counts

---

## 📈 Visualizations Created

### Distribution Analysis

- Product Price Distribution
- Payment Value Distribution

### Revenue Analysis

- Top Revenue Generating States

### Payment Analysis

- Payment Type Pie Chart
- Payment Type Distribution

### Order Analysis

- Order Status Count Plot
- Order Status by Payment Type

### Relationship Analysis

- Product Price vs Payment Value
- Product Price vs Freight Value

### Trend Analysis

- Daily Orders Trend

### Advanced Visualizations

- Heatmap Correlation Matrix
- Violin Plots
- Pair Plots
- Scatter Plots

---

## 🔍 Key Insights

### Revenue Insights

- Revenue varies significantly across states.
- A few states contribute a major share of total revenue.

### Payment Insights

- Credit card payments dominate transactions.
- Different payment methods show varying spending behavior.

### Product Insights

- Product prices have a highly skewed distribution.
- Most purchases occur in lower and medium price ranges.

### Order Insights

- Delivered orders form the majority of transactions.
- Order status distribution helps evaluate operational efficiency.

### Customer Behavior

- Daily order trends reveal fluctuations in purchasing activity.
- Payment installments influence overall payment value.

---

## 📊 Sample Business Questions Answered

- Which states generate the highest revenue?
- What payment methods are most preferred?
- How does product price affect payment value?
- What is the trend of daily orders?
- Which order statuses occur most frequently?

---

## 📁 Project Structure

```text
summertraining/
│
├── week1 miniproject.ipynb
├── olist_customers_dataset.csv
├── olist_orders_dataset.csv
├── olist_order_items_dataset.csv
├── olist_order_payments_dataset.csv
├── olist_products_dataset.csv
├── olist_cleaned_dataset.csv
└── README.md
```

---

## ▶️ How to Run

### Clone Repository

```bash
git clone https://github.com/mayankkumarlinghe-jpg/summertraining.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```text
week1 miniproject.ipynb
```

---

## 📤 Output

The project generates:

- Cleaned Dataset (`olist_cleaned_dataset.csv`)
- Statistical Reports
- Revenue Analysis
- Customer Insights
- Interactive Visualizations

---

## 🚀 Future Improvements

- Dashboard Development using Power BI/Tableau
- Customer Segmentation
- Sales Forecasting
- Delivery Time Analysis
- Machine Learning Models for Revenue Prediction

---

## 👨‍💻 Author

**Mayank Kumar**

GitHub: https://github.com/mayankkumarlinghe-jpg

---

⭐ If you found this project useful, consider giving the repository a star.
