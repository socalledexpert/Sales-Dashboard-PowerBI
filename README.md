# Sales-Dashboard-PowerBI

# E-Commerce Sales Dashboard | Power BI

## Project Overview

This project analyzes sales performance for an e-commerce business using Power BI. The dashboard provides insights into revenue generation, customer purchasing behavior, product category performance, payment preferences, and regional sales distribution. The goal is to support data-driven decision-making by identifying key revenue drivers, high-performing regions, and customer transaction patterns.

---

## Business Problem

E-commerce businesses generate large volumes of transactional data daily. Without proper visualization and analysis, it becomes difficult for management to:

* Track overall sales performance
* Identify top-performing product categories
* Understand customer payment preferences
* Evaluate regional revenue contributions
* Monitor sales trends over time
* Support strategic business decisions with data

This dashboard addresses these challenges by transforming raw transactional data into actionable business insights.

---

## Dataset

The project uses the Brazilian E-Commerce Public Dataset (Olist), which contains information related to:

* Orders
* Products
* Customers
* Payments
* Order Items

The data was cleaned, transformed, and modeled in Power BI to establish relationships between tables and generate meaningful business metrics.

---

## Data Preparation

The following data preparation steps were performed:

* Removed unnecessary columns
* Renamed fields for readability
* Corrected data types
* Handled missing category values
* Created relationships between tables
* Built a star-schema style data model
* Created DAX measures for key business metrics

---

## Key Performance Indicators (KPIs)

### 1. Total Revenue

**Definition:** Total sales value generated from all customer payments.

**Formula:**
Revenue = Sum of Payment Value

**Business Importance:**
Measures overall business performance and sales growth.

---

### 2. Total Orders

**Definition:** Total number of unique orders placed by customers.

**Formula:**
Distinct Count of Order IDs

**Business Importance:**
Indicates transaction volume and customer activity.

---

### 3. Average Order Value (AOV)

**Definition:** Average revenue generated per order.

**Formula:**
AOV = Total Revenue ÷ Total Orders

**Business Importance:**
Helps evaluate customer spending behavior and effectiveness of sales strategies.

---

## Dashboard Components

### Sales Trend Analysis

A line chart displaying revenue trends over time.

**Purpose:**

* Identify seasonality
* Detect growth patterns
* Monitor business performance over different periods

---

### Revenue by State

A bar chart comparing revenue generated across states.

**Purpose:**

* Identify high-performing regions
* Support regional marketing and expansion strategies
* Allocate resources effectively

---

### Revenue by Category

A bar chart showing sales contribution by product category.

**Purpose:**

* Identify best-selling categories
* Support inventory planning
* Guide product promotion decisions

---

### Revenue by Payment Type

A donut chart displaying customer payment preferences.

**Purpose:**

* Understand customer transaction behavior
* Optimize payment infrastructure
* Improve customer experience

---

### Interactive Filters

The dashboard includes slicers for:

* State
* Product Category
* Order Status

These allow users to perform dynamic analysis and explore specific business segments.

---

## Key Insights

### Regional Performance

* São Paulo contributes the highest share of revenue among all states.
* Revenue is concentrated in a few major regions, indicating potential opportunities for expansion.

### Product Performance

* Beauty and health products are among the highest revenue-generating categories.
* Product category analysis can support inventory and promotional planning.

### Payment Behavior

* Credit cards account for the majority of transactions.
* Alternative payment methods contribute significantly less revenue.

### Sales Trends

* Revenue shows steady growth across the analysis period.
* Seasonal peaks indicate periods of increased customer demand.

---

## Business Recommendations

### 1. Focus on High-Revenue Regions

Increase marketing efforts and customer retention initiatives in top-performing states while exploring growth opportunities in lower-performing regions.

### 2. Expand High-Performing Categories

Prioritize inventory management and promotional campaigns for top-selling categories to maximize revenue.

### 3. Optimize Payment Experience

Since most customers prefer credit card payments, ensure smooth payment processing while encouraging adoption of alternative payment methods.

### 4. Leverage Seasonal Demand

Use historical sales trends to prepare inventory and marketing campaigns ahead of peak sales periods.

---

## Tools Used

* Power BI Desktop
* Power Query
* DAX (Data Analysis Expressions)
* Data Modeling
* Data Visualization

---

## Skills Demonstrated

* Business Intelligence
* Data Cleaning and Transformation
* Data Modeling
* DAX Measure Creation
* KPI Development
* Dashboard Design
* Business Analysis
* Data Visualization
* Insight Generation
* Decision Support Analytics

---

## Conclusion

The E-Commerce Sales Dashboard transforms transactional data into actionable business insights by tracking revenue, orders, product performance, payment behavior, and regional trends. The dashboard enables stakeholders to monitor business performance, identify growth opportunities, and make informed strategic decisions.
