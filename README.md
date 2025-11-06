# **Meta-Ad-Performance-Dashboard**

## 1. Executive Summary :
This project aims to develop an advanced, real-time Meta Ad Performance Dashboard using  PowerBI to track,analyze, and optimize advertising campaigns running on Facebook and Instagram. The dashboard will provide a complete funnel view, from initial awareness (Impressions) through engagement (Clicks, Shares, Comments) to final conversion (Purchases). By consolidating complex, multi-table data into clear visualizations, the goal is to empower the marketing team to quickly identify audience engagement patterns, optimize budget allocation toward high-ROI campaigns, and diagnose conversion bottlenecks to maximize overall return on investment (ROI).

## 2. Problem Statement :
 Background :  
 While Meta (Facebook and Instagram) platforms generate vast amounts of campaign data, the marketing team lacks an integrated,    real-time tool to comprehensively track performance across all key metrics and demographic/geographic segments. The existing challenge is a “leaky” conversion funnel: ads show high Click-Through Rates (CTR of 11.76%) and Engagement Rates
(13.56%), but suffer from a low Purchase Rate(0.61%), indicating that interest is high but conversions are low.    

 Objective :  
 To create adynamic, single-source-of-truth dashboard that moves beyondsurface-level metrics to clearly isolate where the ad funnel is failing and provide data-backed recommendations to improve purchase efficiency and overall campaign performance.

 Scope :    
 The dashboard will be scoped to include paid advertising campaigns running exclusively on Facebook and Instagram.Key   analyses will include:  
 • Full-Funnel Performance (Awareness, Engagement, Conversion).  
 • Audience Segmentation by Gender and Age.   
 • Time-Based Analysis (Weekly Trends, Hourly Trends, Seasonal Heat Map).  
 • Comparative Ad Type Performance (Video, Stories, Image, Carousel).  

 ## 3. Data Sources :  
 Primary Data :  
 • Real-time ad performance data (3 4 months of history).  
 • Multi-table data structure: The main fact table is ad_events, linked to dimension tables for
 users, ads, and campaigns.  
 • Adedicated Calendar/Date table will be utilized for time-based analysis and heat maps.  

 Secondary Data :  
 • Industry benchmark data for CTR and Engagement Rates (used for context in interpretation).  

 ## 4. Methodology :  
 Data Integration :  
 Raw data will be sourced from internal data warehouses and integrated into Power BI. An advanced data model utilizing a Snowflake Schema will be implemented to connect the central ad_events fact table with multiple dimension tables, ensuring efficient filtering and cross-table metric calculation.
 
 Dashboard Design :  
 The design will feature seven primary visualizations, including KPIs,a Calendar Heat Map, a Stacked Column Chart for weekly  trends by ad type, and an Area Chart for hourly trends. A Matrix visualization will provide side-by-side performance comparison of Ad Types vs Platforms.  
 
 Interactivity :  
 DAX(Data Analysis Expressions) will be heavily utilized to create complex,calculated KPIs such as Click-Through Rate (CTR), Conversion Rate, and Engagement Rate.Interactive slicers and filters will allow users to drill down by campaign, platform (Facebook/Instagram), and date range.

 ## 5. Expected Outcomes :  
 • A comprehensive, visually compelling Power BI dashboard for real-time Meta ad monitoring.  
 • Key Insight Delivery: Clear identification of the high-value audience(e.g.,Females,18 30) and low-efficiency audience  segments.  
 • Budget Optimization: Data-driven recommendation to shift budget allocation towards best-performing ad formats (Video and Stories).  
 • Conversion Strategy: Diagnosis of the funnel bottleneck and actionable recommendations to improve landing page experience and retargeting efforts.  

## 6. Tools and Technologies :  
 • Power BI – Core tool for data modeling, DAX calculation, and visualization.  
 • Microsoft Excel – For initial raw data inspection, cleaning, and preparation before loading into Power BI.  
 • DAX – Essential for creating all derived and custom calculated metrics on the dashboard.

 ## 7. Risks and Challenges :  
 • Data Latency: Given the real-time nature of ad data, ensuring low latency during refresh cycles from the source systems to Power BI Service.  
 • Integration Complexity: Successfully establishing the multi-table Snowflake Schema with out creating circular dependencies or performance slowdowns.  
 • DAX Precision: Ensuring the accuracy and stability of complex DAX formulas used for critical financial KPIs like Conversion Rate and Purchase Rate.  

 ## 8. Conclusion :  
 The Meta Ad Performance Dashboard project is a high-value initiative that directly addresses the core business need of maximizing advertising ROI. By providing a 360-degree view of campaign performance,   from awareness to purchase,this PowerBI solution will not only track metrics but also generate the critical, actionable insights necessary for the marketing team to optimize their budget, refine their targeting, and ultimately solve the current low purchase rate problem. The clear, interactive design will ensure the data is accessible and impactful across all stakeholder levels.
