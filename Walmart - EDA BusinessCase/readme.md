# Walmart Black Friday Purchase Behavior Analysis

## About Walmart

Walmart is a leading American multinational retail corporation that operates a chain of supercenters, discount department stores, and grocery stores. With over 100 million customers globally, Walmart focuses on delivering low prices and a wide selection of goods.

## Business Objective

The management team at Walmart wants to analyze customer purchase behavior during Black Friday, particularly focusing on purchase amount by gender and other demographic attributes. 

## The key question:

Do women spend more than men on Black Friday?
Further analysis includes purchase differences based on marital status and age groups to derive actionable insights for personalized marketing and improved inventory planning.

## Dataset Overview

The dataset Walmart_data.csv contains transactional data from customers who purchased products at Walmart on Black Friday. The features included are:

User_ID: Unique ID of the customer

Product_ID: Unique ID of the product

Gender: Male or Female

Age: Age group (binned)

Occupation: Occupation of the customer (masked)

City_Category: Category of the city (A, B, C)

StayInCurrentCityYears: Number of years the customer has stayed in their current city

Marital_Status: 0 = Single, 1 = Married

ProductCategory: Product category (masked)

Purchase: Purchase amount in dollars

## What Good Looks Like?

### 1. Data Exploration & Cleaning

Load and inspect the dataset using head(), info(), and describe().

Identify missing values using isnull() and handle appropriately.

Detect outliers in Purchase using boxplots and check skewness.

Compare mean vs median in Purchase to assess skew.

### 2. Univariate & Bivariate Analysis

Plot distribution of Purchase for different customer segments (e.g., Gender, Marital_Status, Age).

Use boxplots to compare purchase patterns by demographic features.

Analyze frequency of purchases across City_Category and Occupation.

### 3. Gender-Based Purchase Patterns

Calculate and compare average purchase by male and female customers.

Visualize purchase trends using histograms and bar plots.

Compute and interpret confidence intervals for male and female average purchases using the Central Limit Theorem.

Try different sample sizes (e.g., 100, 500, 1000) and confidence levels (90%, 95%, 99%).

Observe overlap or divergence in intervals.

### 4. Purchase Analysis by Marital Status and Age

Compare average purchases between Married and Unmarried customers.

Analyze purchase patterns across age groups, mapped to life stages:

0–17 (Teenagers)

18–25 (Young Adults)

26–35 (Early Adults)

36–50 (Mature Adults)

51+ (Older Adults)

### 5. Statistical Inference and Confidence Intervals

Use sample data to infer population mean purchases.

Apply Central Limit Theorem (CLT) to simulate sampling distribution.

Calculate confidence intervals for:

Gender-based spending

Marital status-based spending

Age group-based spending

Observe interval width and interpret overlap.

### 6. Segmentation & Customer Profiling

Profile customers by Gender, Marital Status, and Age with respect to:

Average Purchase

Frequency of high-value purchases

Category-wise preferences (if available)

Cluster similar behavior groups to help marketing teams build campaigns.

### 7. Recommendations & Insights

## Key Questions Answered:

Do females spend more than males during Black Friday?

Are married individuals spending more than singles?

Which age group is the biggest spender?

Do confidence intervals support these conclusions?

## Actionable Recommendations:

Personalized Marketing: Target higher-spending demographics with exclusive offers.

Product Placement: Promote high-value items to top-spending segments (e.g., 26–35 age group or married women).

Inventory Optimization: Forecast demand more accurately by analyzing city-wise and demographic purchase patterns.

Customer Loyalty Programs: Design targeted programs based on purchase trends of different segments.

## Outcome

## This analysis will help Walmart:

Understand demographic-wise purchase behavior.

Make data-driven decisions on marketing and promotions.

Improve customer experience through targeted offerings.

Align supply chain and inventory with real demand patterns.
