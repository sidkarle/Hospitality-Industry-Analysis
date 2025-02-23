# Hospitality-Industry-Analysis
📌 Overview
This Power BI dashboard provides an interactive analysis of key performance metrics in the hospitality industry, including revenue, occupancy rates, ADR (Average Daily Rate), RevPAR (Revenue per Available Room), and booking trends. The goal is to enable hotel managers and stakeholders to make data-driven decisions for improving pricing strategies and revenue optimization.

🚀 Features
✅ Revenue & Occupancy Analysis: Monitors revenue trends, occupancy %, realization %, and ADR across different hotels and cities.
✅ City-Wise Revenue Insights: Compares hotel revenue across Mumbai, Bangalore, Hyderabad, and Delhi for performance benchmarking.
✅ Weekday vs. Weekend Analysis: Tracks occupancy, ADR, and realization rate differences between weekdays and weekends.
✅ Booking Platform Performance: Analyzes revenue & realization % for different platforms (Tripster, Direct-Q, Journey, etc.).
✅ Weekly Trends & Forecasting: Visualizes RevPAR, ADR, and occupancy % trends over different weeks for demand forecasting.
✅ Hotel Performance Metrics: Displays Revenue, Occupancy %, ADR, Cancellations, and Ratings for individual properties.

🗂 Data Model & Structure
This project uses a star schema data model for efficient analysis. The key tables include:
📌 dim_hotels: Contains hotel details (property name, city, category).
📌 fact_bookings: Stores all booking transactions, including revenue, occupancy, and ratings.
📌 dim_rooms: Manages room categories and types.
📌 dim_date: Provides time-based trend analysis for daily, weekly, and monthly insights.
📌 fact_aggregated_booking: Aggregates successful bookings, capacity, and realization metrics.

📂 Dataset & Source:
I have uploaded the dataset for this project in my repo.
