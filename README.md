**Amazon Product Sales Data Analytics**

📊 **Project Overview**

This project analyzes Amazon product sales and performance data using Microsoft Excel and Power BI.

The objective is to clean and prepare the dataset, analyze product ratings, reviews, pricing, discounts, purchases, sponsorship, coupons, and best-seller performance, and present the findings through an interactive Power BI dashboard.

🎯 **Objectives**

Clean and preprocess the Amazon product dataset using Excel.

Handle missing values and standardize data.

Convert and prepare purchase and price-related fields for analysis.

Create calculated fields and DAX measures in Power BI.

Analyze product ratings, reviews, pricing, discounts, purchases, coupons, sponsorship, and best-seller status.

Build an interactive multi-page Power BI dashboard.

Present key insights and recommendations based on the analysis.

📁 **Dataset**

Dataset: Amazon Product Sales Data 42K+ Items - 2025
Source: Kaggle
Dataset URL: https://www.kaggle.com/datasets/srisyra02/amazon-product-sales-data-42k-items-2025

The dataset contains more than 42,000 Amazon product records collected in 2025.

🛠️ **Tools Used**

Microsoft Excel – data cleaning, preprocessing, missing-value handling, and initial analysis

Power BI – data modeling, DAX calculations, interactive visualizations, and dashboard creation

🧹 **Data Cleaning & Preparation**

The Excel preprocessing included:

Duplicate record checking

Missing-value analysis and treatment

Median imputation for rating and number of reviews

Conversion of monthly purchase information into numeric values

Creation of purchase data status

Cleaning and standardization of price fields

Preparation of original and discounted prices

Cleaning of delivery date information

Retention of unavailable Buy Box information as Not Available

Removal of unnecessary fields after extracting the required information

📈 **Power BI Dashboard**

The final Power BI report contains six pages:

1. Executive Overview

Provides an overall summary using KPI cards, product ratings, sponsored vs. organic listings, coupon usage, and price categories.

2. Product Analytics

Analyzes product ratings, reviews, and monthly purchases across rating categories.

3. Pricing & Discount Analytics

Examines original prices, discounted prices, discount percentages, reviews, and coupon usage.

4. Performance Analysis

Analyzes monthly purchases, ratings, reviews, price categories, sponsored listings, and best-seller performance.

5. Product Details

Provides product-level information through an interactive drill-through page.

6. Insights & Recommendations

Summarizes the key findings from the analysis and provides actionable recommendations.

📌 **Key Insights**

Products generally show strong customer ratings, with a large share falling into the higher rating categories.

The dataset contains a substantial volume of customer reviews.

Coupon usage is limited compared with products without coupons.

Most product listings are organic rather than sponsored.

Pricing and discount patterns vary across products and rating levels.

Customer reviews and product ratings provide useful indicators for understanding product performance.

💡 **Recommendations**

Strengthen the visibility and promotion of highly rated products.

Optimize discount and coupon strategies where appropriate.

Investigate lower-rated products and identify opportunities to improve customer satisfaction.

Use customer reviews to identify product strengths and areas for improvement.

Balance sponsored promotions with strong organic product performance.

📂 **Repository Structure**

Amazon-Sales-Data-Analytics/
│
├── README.md
├── Project_Guidelines.pdf
│
├── Excel/
│   └── Amazon_Sales_Data_Cleaned.xlsx
│
├── PowerBI/
│   └── Amazon_Sales_Dashboard.pbix
│
├── Documentation/
│   └── Project_Report.md
│
└── Screenshots/
    ├── 01_Executive_Overview.png
    ├── 02_Product_Analytics.png
    ├── 03_Pricing_Discount_Analytics.png
    ├── 04_Performance_Analysis.png
    ├── 05_Product_Details.png
    └── 06_Insights_Recommendations.png

🔍 **Project Outcome**

The project demonstrates an end-to-end data analytics workflow, from raw data cleaning and preprocessing in Excel to data modeling, DAX calculations, interactive dashboard development, and insight generation in Power BI.

Tools: Excel | Power BI | DAX
Dataset Source: Kaggle
