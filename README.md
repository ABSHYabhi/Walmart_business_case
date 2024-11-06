# Walmart Customer Purchase Behavior Analysis

This project analyzes Walmart's customer purchase behavior based on multiple factors like age, gender, marital status, and more. By examining these variables, this exploratory data analysis (EDA) aims to uncover insights that can help Walmart's management team make data-driven business decisions.

## Dataset
The dataset contains information about customer demographics and their purchase data. You can download the dataset from the following link:
[Walmart Customer Purchase Dataset](https://drive.google.com/file/d/1dnvHRU8U2VFLR1pG46P2PnNm26ebANR4/view?usp=drive_link)

### Features in the Dataset:
- `User_ID`: Unique user ID
- `Product_ID`: Unique product ID
- `Gender`: Gender of the user
- `Age`: Age of the user, binned into groups
- `Occupation`: Occupation code of the user
- `City_Category`: Category of the city (A, B, or C)
- `StayInCurrentCityYears`: Number of years spent in the current city
- `Marital_Status`: Marital status of the user
- `ProductCategory`: Category of the product
- `Purchase`: Amount spent on the purchase

## Project Structure
- **Data Cleaning**: Checking for missing values and handling them as appropriate.
- **Outlier Detection**: Detecting and clipping outliers within the 5th and 95th percentile range.
- **Exploratory Data Analysis (EDA)**:
  - Analyzing purchase behavior across different demographic groups.
  - Visualizing the distribution of age, gender, occupation, and product categories.
  - Examining correlations between gender, age, marital status, and purchase amount.
  - Understanding spending patterns across different city categories and occupation types.

## Analysis Breakdown

### 1. Initial Data Analysis
   - **Data Types**: Displayed the data types of each column.
   - **Shape of Dataset**: Showed the number of rows and columns.
   - **Missing Values**: Identified and counted missing values in each column.

### 2. Outliers and Null Value Detection
   - **Outliers**: Used box plots to detect outliers for continuous variables.
   - **Clipping**: Clipped data between the 5th and 95th percentiles.

### 3. Data Exploration
   - **Age Groups vs. Product Categories**: Examined product preferences among different age groups.
   - **Age, Marital Status, and Spending**: Investigated relationships between age, marital status, and amount spent.
   - **Gender-Based Product Preferences**: Compared product categories across genders.

### 4. Gender and Purchase Behavior
   - **Central Limit Theorem & Bootstrapping**: Computed 95% confidence intervals for average purchase amounts per gender.
   - **Sample Sizes**: Analyzed the effect of sample size (300, 3000, 30000) on confidence intervals and distribution shapes.

### 5. Marital Status and Purchase Behavior
   - **Confidence Intervals by Marital Status**: Used bootstrapping to analyze average spending by marital status with different sample sizes.

### 6. Age and Purchase Behavior
   - **Age-Based Spending Patterns**: Computed confidence intervals to observe the impact of age on spending.

## Results and Insights

- **Gender-Based Spending**: Observed if the confidence intervals for males and females overlap, helping identify gender-based spending patterns.
- **Marital Status Impact**: Checked if the confidence intervals for married vs. unmarried individuals overlap, offering insights into marital status-based spending.
- **Age Group Spending Trends**: Analyzed overlap in confidence intervals across age groups to provide age-based recommendations.

## Recommendations

Based on the analysis, the following recommendations are suggested for Walmart:

1. **Personalized Marketing**: Design targeted marketing campaigns for high-spending customer segments, such as specific age groups or marital statuses that exhibit higher purchase behaviors.
2. **Product Recommendations**: Tailor product recommendations based on gender and age-based preferences to improve sales and customer satisfaction.
3. **City-Specific Promotions**: Create city-specific promotions, leveraging the differences in purchasing power and preferences by city category.
4. **Event-Based Campaigns**: Implement promotions during peak buying times such as Black Friday, especially targeting demographics observed to have high spending during such events.
5. **Customer Retention Strategies**: Develop retention strategies for demographic groups with lower spending to boost overall revenue.


