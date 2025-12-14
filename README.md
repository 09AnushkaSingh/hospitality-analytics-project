# Hospitality Analytics: Exploratory Data Analysis (EDA) using Python 

## Project Overview
Project Type: Exploratory Data Analysis (EDA)
Skills Demonstrated: Data Cleaning, EDA, Business Insights, Visualization 

This project presents a comprehensive, data-driven analysis of hotel booking, occupancy and revenue performance for AtliQ Hotels, a fictional hospitality brand. The goal of this analysis is to understand how customers book rooms, how hotel categories perform across cities and what factors influence revenue generation.

Using Python and real world analytics workflows, this project uncovers patterns in booking behavior, occupancy efficiency, revenue distribution, customer satisfaction and platform wise booking trends. These insights help hospitality businesses make informed decisions related to pricing, marketing, demand forecasting and operational optimization.


## Problem Statement & Objectives
The hospitality industry depends heavily on demand forecasting, customer behavior analysis and revenue management. AtliQ Hotels seeks to leverage data to understand:
* What drives occupancy across hotel categories and cities
* Why revenue fluctuates across platforms, months and segments
* How customer ratings impact performance
* How aggregated and individual booking behavior influence business outcomes
  
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

## Tools Used
* Python: Pandas, NumPy, Matplotlib, Seaborn
* Jupyter Notebook
* Techniques Applied:
     * Data cleaning & preprocessing
     * Handling missing values & inconsistent formats
     * Exploratory Data Analysis (EDA)
     * Statistical aggregation & group-by analysis
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
     * All charts, insights, and conclusions

## Author
* Name: Anushka Singh
* Institution: Gokhale Institute of Politics and Economics
* Github: https://github.com/09AnushkaSingh
* Linkedin: https://www.linkedin.com/in/anushka09singh/
* Date: November 2025
