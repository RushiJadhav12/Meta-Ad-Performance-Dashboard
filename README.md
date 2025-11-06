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
