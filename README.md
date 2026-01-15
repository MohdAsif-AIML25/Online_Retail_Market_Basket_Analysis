# Online_Retail_Market_Basket_Analysis

## AIM OF THE PROJECT

The aim of this project is to analyze an online retail dataset to understand customer purchasing behavior and to discover meaningful relationships between products using data analytics and association rule mining techniques. The project focuses on identifying frequently purchased product combinations that can support business decision-making such as cross-selling, product bundling, and recommendation systems.

## 📘 PROJECT DESCRIPTION

This project uses the Online Retail Dataset to perform:

Data preprocessing and cleaning

Exploratory Data Analysis (EDA)

Feature engineering

Correlation analysis

Association rule mining using Apriori and FP-Growth algorithms

The dataset contains transactional records of an online retail store, including product descriptions, quantities, prices, invoice details, and customer information. By applying data mining techniques, the project extracts hidden patterns and associations among products that customers frequently buy together.

## 🛠️ WHAT IS DONE IN THE PROJECT

The following tasks are carried out:

Loaded and explored the online retail dataset

Cleaned the data by removing missing values, cancelled orders, and invalid records

Created new features such as Total Price, Month, and Hour

## Performed Exploratory Data Analysis to:

Identify best-selling products

Find revenue-generating products

Analyze sales by country, month, and time

Analyzed correlations between quantity, price, and total sales

Prepared transactional data for association rule mining

Applied Apriori and FP-Growth algorithms

Compared the performance and results of both algorithms

Interpreted results to generate business insights

## ⚙️ HOW THE PROJECT IS DONE (METHODOLOGY)
### Step 1: Data Collection

The Online Retail dataset is imported using Python libraries such as Pandas.

### Step 2: Data Preprocessing

Removed records with missing Customer IDs

Eliminated cancelled transactions

Filtered out negative quantities and prices

Cleaned product descriptions

### Step 3: Feature Engineering

Created TotalPrice = Quantity × UnitPrice

Extracted time-based features such as Month and Hour

### Step 4: Exploratory Data Analysis (EDA)

Visualizations were created using Matplotlib and Seaborn to analyze:

Top-selling products

Revenue contribution

Country-wise sales distribution

Monthly and hourly sales trends

### Step 5: Association Rule Mining

Transaction data was transformed into a basket format

Apriori algorithm was applied to generate frequent itemsets and rules

FP-Growth algorithm was used for faster rule generation

Rules were evaluated using support, confidence, and lift

### Step 6: Interpretation and Comparison

Apriori and FP-Growth results were compared

High-confidence and high-lift rules were selected for insights

## 📊 FINAL OUTPUT OF THE PROJECT

The project produces the following outputs:

Cleaned and processed dataset

Visual insights through charts and graphs

List of top-selling and high-revenue products

Country-wise and time-based sales trends

Strong association rules showing frequently bought product combinations

Comparison of Apriori and FP-Growth algorithms

Business-oriented insights for decision-making

## 🧠 WHAT WE UNDERSTAND FROM THE PROJECT

From this analysis, we understand that:

Certain products are consistently purchased together

High sales volume does not always mean high revenue

A few countries contribute the majority of total sales

Sales follow time-based patterns (monthly and hourly)

FP-Growth is faster and more efficient than Apriori for large datasets

Association rules can effectively support marketing and recommendation strategies

## 🏁 FINAL CONCLUSION

This project successfully demonstrates how data analysis and association rule mining can be used to extract valuable insights from retail transaction data. Through effective data preprocessing, visualization, and application of Apriori and FP-Growth algorithms, meaningful product relationships were identified.

The findings of this project can help businesses:

Improve cross-selling strategies

Design effective product bundles

Optimize inventory management

Build personalized recommendation systems

Overall, the project highlights the importance of data-driven decision-making in the retail industry and shows how machine learning and data mining techniques can add significant business value.
