#Automobile Price Analysis Using Python

📌 Project Overview

This project performs Exploratory Data Analysis (EDA) on an automobile dataset to identify the key factors influencing car prices.

The objective is to understand how features such as engine size, fuel type, body style, and brand affect vehicle pricing and to extract meaningful business insights using Python.

🎯 Business Objective

To answer the following key questions:

What factors most strongly influence car prices?

How does engine size relate to price?

Which car brands dominate the dataset?

How do fuel type and aspiration affect pricing?

Which body styles are positioned in premium vs budget segments?

🛠️ Tools & Technologies Used

Python

Pandas

NumPy

Matplotlib

Seaborn

Google Colab

📊 Analysis Performed
1️⃣ Univariate Analysis

Distribution of engine size (Histogram + KDE)

Boxplot to detect outliers in engine size

Count plot of car makes

2️⃣ Bivariate Analysis

Engine size vs price (Scatter plot)

Price vs symboling (risk rating)

Price distribution by body style

Clustered bar plot (Fuel type & Aspiration vs Price)

3️⃣ Aggregation & Group Analysis

Average price by car make using groupby

Identified premium and economical brands

4️⃣ Correlation Analysis

Pairplot for numerical relationships

Heatmap of correlation matrix

Identified strong positive correlation between engine size and price

🔎 Key Insights

Engine size shows strong positive correlation with price, indicating larger engines are typically associated with higher vehicle cost.

Premium brands such as Jaguar and Mercedes-Benz have significantly higher average prices.

Turbocharged vehicles tend to have higher pricing compared to standard aspiration models.

Convertible and hardtop body styles fall into higher price segments.

Hatchbacks are generally positioned in the economical segment.

📈 Conclusion

The analysis indicates that engine size, brand positioning, body style, and aspiration type are major drivers of vehicle pricing.

This study demonstrates practical application of:

Data cleaning

Exploratory data analysis

Visualization techniques

Business insight extraction

📂 Dataset

The dataset used is a structured automobile dataset containing features such as:

Engine size

Price

Make

Fuel type

Aspiration

Body style

Symboling

And other vehicle specifications
