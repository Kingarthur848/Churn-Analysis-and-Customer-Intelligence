# 📊 Churn Analysis and Customer Intelligence

An end-to-end customer churn analysis project using **Python, Pandas, NumPy, SQL, SQLite, Matplotlib, and Seaborn** to clean customer data, analyze customer behavior, and identify factors associated with customer churn.

## 📌 Project Overview

Customer churn is an important business problem because losing customers can directly impact revenue and growth.

In this project, customer, subscription, and support data are analyzed to understand customer characteristics, subscription behavior, support interactions, and churn-related patterns.

The project follows a complete data analysis workflow:

**Data Import → Data Cleaning → Data Transformation → SQL Analysis → Exploratory Data Analysis → Churn Analysis → Insights**

## 🛠️ Technologies Used

- **Python**
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **SQLite** – Database management and SQL analysis
- **Jupyter Notebook** – Analysis environment

## 📂 Dataset Structure

The project works with three main tables:

### 1. Customer

Contains customer demographic information:

- Customer ID
- Customer Name
- Country
- State
- Gender
- Date of Birth
- Interests
- Pincode

### 2. Subscription

Contains customer subscription information:

- Customer ID
- Subscription Start Date
- Subscription Type
- Renewal Date
- Plan Type
- Contract Type
- Cancellation Date
- Cancellation Reason
- Monthly Charges
- CLTV
- Churn Score

### 3. Support

Contains customer support information:

- Customer ID
- Complaint Date
- Escalations
- CSAT Score
- Comments

## 🧹 Data Cleaning

The project includes several data-cleaning and preprocessing steps, including:

- Renaming columns for consistency
- Removing unnecessary columns
- Handling missing values
- Converting data types
- Standardizing categorical values
- Cleaning customer demographic information
- Preparing datasets for analysis

For example, gender values such as `Men` and `Women` are standardized to `Male` and `Female`.

## 🗄️ SQLite Database

The raw Excel data is converted into a SQLite database.

The workflow includes:

1. Reading Excel sheets using Pandas
2. Creating a SQLite database
3. Converting individual Excel sheets into SQLite tables
4. Querying SQLite tables using SQL
5. Loading SQL results back into Pandas DataFrames

This provides practice with both **SQL and Python-based data analysis**.

## 📈 Exploratory Data Analysis

The project explores customer and subscription characteristics using Pandas and visualization libraries.

Analysis includes areas such as:

- Customer demographics
- Subscription characteristics
- Monthly charges
- Customer lifetime value (CLTV)
- Churn scores
- Contract types
- Cancellation information
- Customer support interactions
- Escalations
- CSAT scores

## 🔎 Churn Analysis

The main objective is to identify patterns associated with customer churn.

The analysis investigates relationships between churn and different customer attributes, including:

- Customer demographics
- Subscription plans
- Contract types
- Monthly charges
- Customer lifetime value
- Support escalations
- Customer satisfaction
- Cancellation information

## 📊 Visualizations

The project uses:

- Bar charts
- Count plots
- Distribution plots
- Box plots
- Correlation analysis
- Other exploratory visualizations

These visualizations help identify patterns and communicate findings clearly.

## 💡 Key Objectives

- Understand customer characteristics
- Clean and prepare raw customer data
- Analyze customer subscription behavior
- Identify churn-related patterns
- Investigate the relationship between customer support and churn
- Use SQL for structured data analysis
- Generate business-oriented insights from customer data

## 🚀 Project Workflow

```text
Raw Excel Data
       ↓
Data Import
       ↓
SQLite Database
       ↓
SQL Queries
       ↓
Pandas DataFrames
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis
       ↓
Churn Analysis
       ↓
Visualizations & Insights
