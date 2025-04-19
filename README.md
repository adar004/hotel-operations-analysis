# Hotel Operations Data Analysis 🏨📊

This project investigates customer satisfaction and service response times across branches of **LuxurStay Hotels**, a global hotel chain. The analysis helps identify issues in service delivery and target areas for operational improvements.

---

## 🧩 Problem Statement

LuxurStay Hotels received multiple complaints about **slow room services** in certain branches. Customer satisfaction has dropped below their desired threshold of **4.5 out of 5**.  
The goal of this analysis is to uncover root causes and help the Head of Operations address these issues.

---

## 📁 Dataset Description

The project uses 3 tables:

- **Branch**: Metadata about each hotel branch
- **Service**: Types of services offered (e.g., Meal, Laundry)
- **Request**: Customer service requests, ratings, and response times

Relational Schema:
- `Request` links to `Branch` and `Service` via foreign keys

---

## 🎯 Tasks Overview

### 🧼 Task 1: Clean `branch` Table
- Identify and remove invalid values (e.g., missing data, outliers)
- Output: `clean_branch_data`

### ⏱️ Task 2: Analyze Service Time
- Calculate **average** and **maximum** time taken for each service at each branch
- Output: `average_time_service`

### 🌍 Task 3: Target Regions for Improvement
- Focus on **Laundry** and **Meal** services in **Europe (EMEA)** and **Latin America (LATAM)**
- Return service description, branch location, request ID, and rating
- Output: `target_hotels`

### 📉 Task 4: Identify Underperforming Services
- Report service-branch pairs where **average rating < 4.5**
- Output: `average_rating`

---

## 🛠️ Skills & Tools Used

- **SQL-style querying**
- **Data cleaning**
- **Group-by aggregations**
- **Analytical storytelling**

---

## 📌 Key Insights

- Certain branches consistently have longer response times.
- Meal and Laundry services in EMEA and LATAM are lower-rated.
- Some branches fall below the 4.5 satisfaction threshold set by management.

---

## 🔗 Credits

Data and problem provided by [DataCamp](https://www.datacamp.com/), adapted for portfolio purposes.
