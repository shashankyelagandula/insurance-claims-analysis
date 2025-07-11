# Insurance Auto Claims Analysis

## Project Title  
**Analyzing Insurance Auto Claims**

## Introduction  
This project involves working with a dataset of auto claims from an automobile insurance company operating in the southwestern and western United States. The primary goal is to perform exploratory data analysis (EDA) on the `claims_df` dataset and provide actionable insights and recommendations to the executive team to improve pricing strategies, policy offerings, and profitability.

## Data  
The `claims_df` data frame includes **6,249 individual auto insurance claims**, with each row representing a unique claim and its associated customer, policy, and financial attributes.

## Data Definitions

| Variable | Definition | Data Type |
|----------|------------|-----------|
| `customer_id` | Customer identifier | Character |
| `customer_state` | State of residence | Factor |
| `highest_education` | Highest level of education | Factor |
| `employment_status` | Employment status at time of claim | Factor |
| `gender` | Gender | Factor |
| `income` | Income (US Dollars) | Numeric |
| `residence_type` | Customer residence type | Factor |
| `marital_status` | Marital status | Factor |
| `sales_channel` | Customer acquisition method | Factor |
| `coverage` | Auto policy tier | Factor |
| `policy` | Auto policy type | Factor |
| `vehicle_class` | Vehicle type | Factor |
| `vehicle_size` | Vehicle size | Factor |
| `monthly_premium` | Customer monthly premium | Numeric |
| `months_policy_active` | Number of months policy has been active | Numeric |
| `months_since_last_claim` | Number of months since last claim | Numeric |
| `current_claim_amount` | Current claim amount | Numeric |
| `total_claims` | Total number of claims in customer history | Numeric |
| `total_claims_amount` | Total amount of all claims in customer history | Numeric |
| `customer_lifetime_value` | Customer lifetime value (total revenue - total claims cost) | Numeric |

## Recommendations

### 🧩 Customer Segmentation  
Implement targeted marketing strategies based on customer demographics and behavioral patterns identified in the analysis to attract and retain profitable clients.

### 💰 Premium Adjustment  
Leverage the high correlation between **monthly premium** and **Customer Lifetime Value (CLV)** to optimize premium structures and improve overall revenue.

### 🛠️ Product Development  
Use insights from **vehicle type**, **education level**, and **policy types** to launch tailored insurance plans for specific customer groups.

### 🚗 Safe Driving Initiatives  
Promote defensive driving programs and proactive safety measures to help customers reduce accident frequency, increase CLV, and decrease claim costs.

### 🛒 Sales Channel Optimization  
Continuously monitor performance across regions and acquisition channels. Adjust marketing and sales efforts to focus on high-CLV channels.

