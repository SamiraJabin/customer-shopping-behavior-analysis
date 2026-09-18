# Customer Shopping Behavior Analysis

## 📌 Overview

End-to-end Customer Shopping Behavior Analysis using Python, Pandas, PostgreSQL, SQL, and Power BI. Performed data cleaning and EDA, analyzed customer purchasing patterns using SQL, and built an interactive Power BI dashboard to visualize key business insights and KPIs.

**Data Loading → Data Cleaning → EDA → PostgreSQL & SQL Analysis → Power BI Dashboard**

---

## 📊 Dataset

The dataset contains customer shopping information, including:

- Customer demographics
- Items purchased
- Purchase amount
- Purchase frequency
- Discount and promotional usage
- Subscription status
- Shipping type
- Review ratings
- Product categories

---

## 🛠️ Tools & Technologies

- **Python** – Data processing and analysis
- **Pandas** – Data cleaning and manipulation
- **Jupyter Notebook** – Exploratory Data Analysis
- **PostgreSQL** – Database management
- **SQL** – Business and customer behavior analysis
- **Power BI** – Interactive dashboard and data visualization

---

## 🔄 Project Steps

### 1. Data Loading

- Loaded the CSV dataset into Python using Pandas.
- Inspected the dataset structure, columns, and data types.

### 2. Exploratory Data Analysis (EDA)

Performed EDA to understand:

- Dataset dimensions
- Data distributions
- Missing values
- Duplicate records
- Numerical statistics
- Customer purchasing patterns
- Potential outliers

### 3. Data Cleaning & Transformation

- Handled missing values.
- Checked and removed duplicate records where applicable.
- Created derived columns for analysis.
- Categorized customers into age groups.
- Converted purchase frequency into numerical values.

### 4. PostgreSQL & SQL Analysis

- Loaded the cleaned DataFrame into PostgreSQL.
- Created the `customer` table.
- Used SQL queries to answer business questions related to:
  - Revenue
  - Customer purchasing behavior
  - Product performance
  - Discounts and subscriptions
  - Average spending
  - Purchase frequency
  - Category-level analysis

SQL concepts used:

- `GROUP BY`
- `ORDER BY`
- `HAVING`
- `CASE WHEN`
- Aggregate Functions
- Subqueries
- CTEs
- Window Functions
- `ROW_NUMBER()`

### 5. Power BI Dashboard

Built an interactive Power BI dashboard to visualize key customer and sales metrics.

---

## 📈 Dashboard

The Power BI dashboard includes:

- **Number of Customers**
- **Average Review Rating**
- **Average Purchase Amount**
- **Revenue by Category**
- **Sales by Category**
- **Revenue by Age Group**
- **Sales by Age Group**
- **Subscription Status**

### Interactive Filters

The dashboard allows users to filter data by:

- Subscription Status
- Gender
- Category
- Shipping Type

---

## 💡 Key Results & Insights

The analysis provides insights into:

- Customer purchasing behavior across different demographics.
- Revenue and sales performance across product categories.
- Purchasing behavior across different age groups.
- Customer subscription patterns.
- Average purchase amounts and review ratings.
- The relationship between discounts, subscriptions, and purchasing behavior.

The Power BI dashboard provides an interactive way to explore these insights and support data-driven business analysis.

---


git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
