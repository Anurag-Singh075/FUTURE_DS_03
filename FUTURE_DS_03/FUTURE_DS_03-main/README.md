# 📊Marketing Funnel & Conversion Performance Analysis

## ℹ️ Description:
* Marketing Funnel and Conversion Analysis dashboard built using Power BI to evaluate user behavior, channel performance, and revenue contribution.

## 📖 Table of Contents: 

>* Project Overview
>* Dataset Description
>* Tools & Technologies
>* Data Cleaning & Preparation
>* Exploratory Data Analysis (EDA)
>* Key Insights
>* Recommendations
>* How to Use


## 📘 Project Overview

* This project focuses on analyzing marketing funnel performance and conversion behavior using user session data.
* The dashboard provides a comprehensive view of how users move through different stages of the funnel, from initial interaction to final purchase.
* It highlights traffic distribution, channel effectiveness, revenue contribution, and time-based conversion trends.
* The goal is to transform raw data into meaningful insights that support marketing and business decisions.


## 📁 Dataset Description

The dataset consists of user session-level data structured into fact and dimension tables. 
>* The main fact table contains session ID, user interactions, purchase status, revenue, and event dates. 
>* Dimension tables include customer details, product categories, and marketing channels. 


## 🛠️ Tools & Technologies

**Excel**

> Data cleaning | Sorting and filtering | 

**Power Query**

> Data transformation | Data formatting |

**Power BI**

> Data modeling | Dashboard creation | Visualization |

**DAX (Data Analysis Expressions)**

> Creating measures | Calculations and aggregated metrics |
  
 
## 🧹 Data Cleaning & Preparation - Excel
* Standardized data types as per attribute specifications
* Converted date-time fields into a consistent date format
* Removed duplicate records to ensure data accuracy
* Transformed Bonus Flag values from Yes/No to 1/0 for better analysis
* Structured the dataset into two tables: User_Dim and Session_Fact

## 📦 Data Modeling & Visualization - PowerBI
* Developed 5 analytical tables: Channel-wise, Product-wise, Region-wise, and Yearly Sales (focused on purchased data)
* Created calculated columns: Purchase Status and Bonus Status in the Session_Fact table
* Implemented data modeling to establish relationships
* Built DAX measures for enhanced insights
* Designed interactive visuals including Cards, Charts, and Slicers


## 📊 Exploratory Data Analysis (EDA)

* Session data shows a large gap between total sessions and purchases, indicating low conversion efficiency.
* Most users drop off before completing a purchase, highlighting funnel leakage.
* Google Ads contributes the highest traffic, while social media has the lowest share.
* Organic traffic shows relatively better conversion quality compared to other channels.
* Revenue is concentrated in a few product categories, with Electronics leading.
* Conversion trends fluctuate over time, indicating inconsistent performance.

![Dashboard](MFCPA-Dashboard.png)


## 🔍 Key Insights

* Most sessions do not convert into purchases, indicating significant drop-offs in the funnel.
* Google Ads drives the highest traffic and conversions, while social media underperforms.
* Organic traffic shows better conversion quality compared to other channels.
* Electronics is the top revenue-generating category, while Beauty contributes the least.
* Conversion trends are inconsistent over time, showing unstable performance.

## 💡 Recommendations

* The business has strong traffic but low conversion efficiency.
* Improve the checkout process and user experience to reduce drop-offs.
* Focus on high-performing channels like Google Ads and organic traffic.
* Optimize or rethink social media marketing strategies.
* Promote low-performing categories and ensure consistent campaign efforts to stabilize conversions.


## ▶️ How to Use

* Open the dashboard in Power BI Desktop to explore marketing performance.
* Use slicers to filter by channel, product category, or time period.
* Interact with the funnel chart to understand drop-offs at each stage.
* Click on visuals to compare channel performance and conversion rates.
* Hover over charts to view detailed metrics and insights.
* Use the dashboard to analyze user behavior and improve marketing strategies.
  
## 👩‍💻 Author
 > Anurag Singh
