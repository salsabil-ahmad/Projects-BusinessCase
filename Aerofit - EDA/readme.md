# AeroFit Treadmill Customer Profiling & Product Recommendation Analysis

## About AeroFit

AeroFit is a leading brand in the fitness equipment industry, offering a wide range of products including treadmills, exercise bikes, gym equipment, and fitness accessories. The company caters to a diverse audience and is committed to delivering quality and performance.

---

## Business Objective

The goal of this analysis is to help the market research team at AeroFit identify customer characteristics associated with each type of treadmill purchased. This will enable better product recommendations and personalized marketing strategies for new customers.

---

## Dataset Overview

The dataset `Aerofit_treadmill.csv` consists of data collected from customers who purchased a treadmill in the past three months. The features included are:

- **Product Purchased**: KP281, KP481, or KP781
- **Age**: Age of the customer in years
- **Gender**: Male or Female
- **Education**: Years of education completed
- **MaritalStatus**: Single or Partnered
- **Usage**: Planned weekly treadmill usage (number of times)
- **Income**: Annual income (in $)
- **Fitness**: Self-rated fitness level (1 = poor, 5 = excellent)
- **Miles**: Planned weekly mileage (walk/run)

### Product Portfolio

| Product | Target User         | Price  |
|---------|----------------------|--------|
| KP281   | Entry-level          | $1,500 |
| KP481   | Mid-level runners    | $1,750 |
| KP781   | Advanced features    | $2,500 |

---

## What Good Looks Like?

### 1. Data Exploration & Cleaning
- Import the dataset and check structure (`head`, `info`, `describe`).
- Identify missing values and data types.
- Outlier detection using boxplots and summary statistics (look for skewed distributions).

### 2. Univariate & Bivariate Analysis
- Explore the distribution of key numerical features (e.g., Age, Income, Usage, Miles).
- Compare feature distribution across different products using histograms and boxplots.
- Analyze categorical features (Gender, MaritalStatus) using countplots.

### 3. Product Purchase Patterns
- Create a frequency table for treadmill types using `pandas.crosstab`.
- Visualize product preference by demographics (age, gender, marital status).

### 4. Correlation Analysis
- Use heatmaps and pair plots to check correlation among features.
- Identify which features strongly relate to product selection.

### 5. Probabilistic Analysis
- Calculate **marginal probabilities** (e.g., % of customers purchasing each product).
- Calculate **conditional probabilities** (e.g., P(Product=KP781 | Gender=Male)).
- Use two-way contingency tables for deeper insights.

### 6. Customer Profiling
- Group and analyze customers based on product purchased:
  - Average age, income, fitness, and usage
  - Gender and marital status distributions
- Identify typical customer segments for each product type.

### 7. Recommendations & Insights
- Actionable insights based on customer-product associations.
- Suggestions for marketing, pricing, and sales targeting strategies.

---

## Questions to Answer

- What is the probability of a male customer buying a KP781 treadmill?
- Are single people more inclined to buy a particular model?
- How does income or fitness level influence the choice of treadmill?
- What product should be recommended to a low-income, low-usage customer?
- Which treadmill appeals most to fitness-focused users?

---

## Outcome

The analysis will assist in:
- **Tailored marketing strategies** based on customer profiles.
- **Improved product recommendation** system.
- **Targeted product development** based on real usage and expectations.
