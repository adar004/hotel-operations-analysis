# hotel-operations-analysis
Data analysis project investigating service delays and customer satisfaction in LuxurStay Hotels.

📁 Hotel Operations Analysis – Portfolio Project
Project Name: Optimizing Hotel Service Delivery and Satisfaction using Data Analysis

Platform: [DataCamp Project – Practical Exam: Hotel Operations]

Problem Statement:
LuxurStay Hotels, a global hotel chain, has observed a drop in customer satisfaction due to slow room services. As a data analyst, I was tasked with analyzing operational data to identify the root causes and recommend improvements in service efficiency and satisfaction levels.

📌 Project Tasks & Insights
Task 1: Data Cleaning and Validation
Cleaned the branch table by validating data consistency based on schema descriptions.

Removed invalid or null values and ensured accurate data types.

Created a cleaned DataFrame clean_branch_data for further analysis.

Task 2: Service Time Analysis
Aggregated service request data to compute average and maximum time taken for each service per branch.

Created a summary table average_time_service with avg_time_taken and max_time_taken rounded to two decimal places.

Identified which services were most time-consuming in each hotel.

Task 3: Focused Region and Service Analysis
Filtered data to focus on Meal and Laundry services in Europe (EMEA) and Latin America (LATAM) regions.

Created a detailed DataFrame target_hotels showing service descriptions, branch locations, request IDs, and customer ratings.

This helped identify which services and locations needed targeted operational improvements.

Task 4: Low-Performing Service Combinations
Calculated average customer satisfaction ratings by service_id and branch_id.

Filtered for combinations with average rating below 4.5 (management’s target threshold).

Created average_rating DataFrame to spotlight poorly rated services and locations.

🛠️ Tools & Skills Applied

Data cleaning & wrangling

GroupBy, aggregation, filtering

Insight generation

Data storytelling and stakeholder-focused analysis

📈 Key Takeaways
Services with high avg_time_taken often correlated with low satisfaction ratings.

Specific branches (especially in EMEA & LATAM) had operational bottlenecks in delivering Laundry and Meal services.

Strategic interventions in these branches can improve overall customer experience.


