# TheLook Ecommerce Executive Dashboard Analysis

## Overview

This project is an end-to-end Business Intelligence and Data Analysis project focused on evaluating the business performance of **TheLook Ecommerce Platform** through interactive dashboard development and strategic business insight generation.

The project was developed as a Data Analyst Take Home Test Project with the objective of transforming large-scale ecommerce transactional and behavioral data into actionable business insights that support data-driven decision making.

The analysis focuses on four major business domains:

- Customer Acquisition & Behavior
- Product & Revenue Performance
- Fulfillment & Operational Performance
- Returns & Revenue Leakage

---

# Business Background

The ecommerce industry continues to experience rapid growth alongside increasing operational complexity. Companies are required to manage not only revenue growth, but also customer acquisition efficiency, operational scalability, profitability optimization, and revenue leakage caused by product returns.

Several business challenges identified within this project include:

- Increasing competition in customer acquisition
- High product return behavior
- Revenue leakage risk
- Operational scalability challenges
- Profitability optimization across product categories

To address these challenges, this project aims to analyze how customer behavior, product performance, and operational efficiency influence overall business performance and revenue leakage on TheLook Ecommerce platform.

---

# Main Problem Statement

> How do customer behavior, product performance, and operational efficiency influence revenue leakage and overall business performance on TheLook Ecommerce platform?

---

# Supporting Problem Statements

## 1. Customer Acquisition & Behavior
- Traffic source performance
- Customer engagement patterns
- Conversion efficiency analysis

## 2. Product & Revenue Performance
- Profitability comparison
- Product performance distribution
- Revenue contribution analysis by category

## 3. Fulfillment & Operational Performance
- Fulfillment efficiency monitoring
- Operational bottleneck analysis
- Delivery performance impact evaluation

## 4. Returns & Revenue Leakage
- Return rate analysis
- Revenue leakage impact
- Return behavior factor analysis

---

# Dataset Information

## Dataset Source

Dataset used in this project:

- **TheLook Ecommerce BigQuery Dataset**
- Source: https://www.kaggle.com/datasets/mustafakeser4/looker-ecommerce-bigquery-dataset

## Dataset Characteristics

The project uses multiple relational ecommerce datasets consisting of:

| Dataset | Description |
|---|---|
| `users.csv` | Customer demographic information |
| `events.csv` | Customer activity & interaction logs |
| `orders.csv` | Transactional order data |
| `order_items.csv` | Purchased product details |
| `products.csv` | Product catalog information |
| `distribution_centers.csv` | Fulfillment location data |
| `inventory_items.csv` | Inventory & operational data |

### Dataset Highlights
- Millions of customer activity records
- Transactional and behavioral ecommerce data
- Product and operational information
- Historical data from 2019–2024
- Multiple relational analytical tables

---

# Data Preparation Process

Before conducting the analysis, several preprocessing stages were performed to ensure data quality and analytical consistency.

## Data Preparation Workflow

1. Raw Dataset Collection
2. Data Cleaning
3. Null & Duplicate Handling
4. Data Type Validation
5. Feature Engineering
6. Aggregated Analytical Dataset Preparation

### Key Preprocessing Activities
- Missing value checking
- Duplicate validation
- Invalid fulfillment duration handling
- Datetime transformation
- Derived feature creation
- Analytical table aggregation

---

# Analytical Approaches

Several analytical approaches were used throughout the project, including:

- Descriptive Analysis
- Exploratory Data Analysis (EDA)
- Comparative Analysis
- Trend Analysis
- Revenue & Profitability Analysis
- Operational Performance Analysis
- Revenue Leakage Analysis

---

# Dashboard Development

Interactive dashboards were developed using **Power BI** to support business monitoring and executive-level decision making.

## Dashboard Pages

### 1. Executive Overview
High-level monitoring dashboard containing:
- Total Revenue
- Total Orders
- Total Customers
- Return Rate
- Returned Revenue
- Fulfillment Performance

### 2. Customer Acquisition & Behavior
Focuses on:
- Traffic source distribution
- Conversion performance
- Customer engagement trends
- Behavioral activity patterns

### 3. Product & Revenue Performance
Focuses on:
- Revenue contribution by category
- Profit margin comparison
- Revenue growth trends
- Revenue vs profitability analysis

### 4. Returns & Operational Insights
Focuses on:
- Return rate analysis
- Revenue leakage monitoring
- Fulfillment duration trends
- Operational stability analysis

---

# Key Insights

## Customer Acquisition & Behavior
- Email dominates customer acquisition activity.
- Conversion performance across channels remains relatively similar.
- Customer activity shows strong year-over-year growth.

## Product & Revenue Performance
- Revenue is highly concentrated in several product categories.
- High revenue does not always indicate highest profitability.
- Overall revenue shows a strong upward growth trend.

## Fulfillment & Operational Performance
- Fulfillment duration remains relatively stable over time.
- Operational performance shows consistent stability.
- Business growth does not significantly impact fulfillment efficiency.

## Returns & Revenue Leakage
- Return rate remains relatively high across the analysis period.
- Revenue leakage is concentrated in major categories.
- High transaction categories carry higher leakage risk.

---

# Business Recommendations

Based on the analytical findings, several strategic recommendations were proposed:

## Customer Acquisition Strategy
- Implement channel diversification strategy
- Strengthen omnichannel acquisition
- Optimize retargeting and personalized campaigns

## Product & Profitability Strategy
- Implement profitability-driven category strategy
- Optimize pricing and category mix
- Improve margin efficiency on high-revenue products

## Operational Strategy
- Maintain operational scalability strategy
- Improve operational monitoring & forecasting
- Optimize fulfillment coordination and delivery consistency

## Return Prevention Strategy
- Improve product experience and information quality
- Develop return behavior monitoring
- Implement return prevention initiatives

---

# Tools & Technologies

| Tool | Purpose |
|---|---|
| Power BI | Dashboard development & data visualization |
| SQL | Data querying & transformation |
| DAX | KPI calculation & business metrics |
| Python | Data preprocessing & analysis |
| GitHub | Project documentation & portfolio publishing |

---

# Project Outcome

This project demonstrates a complete end-to-end analytical workflow, including:

- Business understanding
- Data preprocessing
- Exploratory data analysis
- Dashboard development
- Business insight generation
- Strategic recommendation development

The final deliverable provides an executive-level business intelligence dashboard capable of supporting strategic and operational decision making within an ecommerce environment.
