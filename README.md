# AtliQ Hotels: Data Cleaning & KPI Analysis (Hospitality EDA)

## Project Overview
**Project Type:** Exploratory Data Analysis (EDA) <br>
**Skills Demonstrated:** Data Cleaning, EDA, Business Insights

This project performs an in-depth Exploratory Data Analysis (EDA) for AtliQ Hotels, a luxury and business hotel chain in India. The primary objective was to clean transactional hospitality data and derive critical business KPIs (Key Performance Indicators) regarding occupancy rates and revenue realization across different cities and room categories.


## Problem Statement & Objectives
AtliQ Hotels management needed to identify performance gaps in their properties across four major cities. This analysis was designed to provide data-driven answers to:
* Which cities exhibit the highest occupancy rates?
* How do weekends affect booking patterns compared to weekdays?
* What is the impact of various booking platforms on total realized revenue?
  
This analysis was conducted to systematically explore booking trends, identify hidden business patterns and support decision making related to pricing strategy, operational efficiency and revenue improvement.


## The main objectives include:
* Analyze occupancy trends across cities, seasons and hotel categories
* Identify revenue drivers across hotel types, room categories and booking channels
* Study customer behavior through ratings, booking status, stay duration and guest counts
* Examine month wise and platform wise booking patterns
* Merge fact and dimension tables to build a clean analytical dataset
* Generate insights that support data driven decisions


## Data Source
The analysis uses five structured CSV datasets, similar to standard data-warehouse design (fact & dimension tables):
* dim_date.csv – Date attributes (month, weekday, year, etc.)
* dim_hotels.csv – Hotel-level info (city, hotel category, property details)
* dim_rooms.csv – Room categories and capacities
* fact_aggregated_bookings.csv – Monthly aggregated occupancy & capacity
* fact_bookings.csv – Individual booking records (platform, guests, ratings, revenue, status)


## Technical Workflow & Analysis
  1. Data Cleaning & Integrity
     * Guest Validation: Removed records with negative guest counts (data entry errors).
     * Revenue Outlier Removal: Implemented the 3-Standard Deviation rule to eliminate invalid revenue entries, preventing skewed averages. 
     * Missing Value Imputation: Filled null capacity values in the aggregate dataset using the median to ensure reporting consistency. 

 **2. Feature Engineering & Transformation** <br>
     * Occupancy KPI: Created the occ_pct (Occupancy Percentage) metric to standardize performance comparison between hotels of different sizes. 
     * Data Merging: Joined dimension tables with fact tables to enable multi-dimensional analysis (e.g., Revenue by City, Occupancy by Room Class). 

 **3. Key Business Insights**
     * City Leaders: Delhi maintains the highest average occupancy (~61.5%) while Mumbai generates the maximum total revenue (~₹668.6M) 
     * Weekly Trends: Occupancy spikes significantly on weekends (~72%) vs. weekdays (~51%), highlighting a strong weekend leisure travel market.
     * Room Performance: Presidential Suites (RT4) maintain a high occupancy rate of ~59%, suggesting strong demand for premium offerings. 


## Project Scope & Technical Depth
**Note to Recruiters: This project specifically focuses on the Data Cleaning, Integrity and Business KPI aspect of EDA.** <br>
* Core Focus: Statistical outlier management (3 sigma) data merging and hospitality-specific metric derivation.  
     * Future Enhancements: Advanced statistical visualizations (Correlation Heatmaps and Bivariate Distributions) are being implemented in my upcoming "Master EDA" project to further explore predictive patterns.  


## Tools Used
* Python: Pandas, NumPy, Matplotlib, Seaborn
* Jupyter Notebook
* Techniques Applied:
     * Data cleaning & preprocessing
     * Handling missing values & inconsistent formats
     * Exploratory Data Analysis (EDA)
     * Trend analysis & visualization


## Key Features & Analyses
* Occupancy Analysis:
Compared occupancy percentages across hotel types, cities, and seasons to identify high-performing and underperforming segments.

* Revenue Insights:
Analyzed city-wise, month-wise, and platform-wise revenue trends to understand business performance patterns.

* Customer Behavior Analysis:
Studied customer ratings, booking status (Cancelled/Checked-out), stay durations, and reservation patterns.

* Platform Analysis:
Compared performance of online travel agencies vs direct bookings.

* Visualization:
Created bar charts, time-series plots, pie charts, and heatmaps to highlight trends and KPIs.

* Merged Dataset Creation:
Combined fact and dimension tables into a unified, analysis-ready dataset for better insights.

## How to View the Report
* Open the Hotels Analysis.ipynb file directly on GitHub or Jupyter Notebook.
* Run the notebook cells sequentially to explore:
     * Data cleaning
     * Feature engineering
     * Exploratory data analysis
     * All charts, insights and conclusions

## Author
* Name: Anushka Singh
* Institution: Gokhale Institute of Politics and Economics
* Github: https://github.com/09AnushkaSingh
* Linkedin: https://www.linkedin.com/in/anushka09singh/
* Date: November 2025
