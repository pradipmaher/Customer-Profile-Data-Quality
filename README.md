# Customer-Profile-Data-Quality

# 📊 Customer Profile Data Quality & Completeness Analysis

## 📌 Project Overview

This project focuses on analyzing **customer profile data quality** to identify missing, incomplete, and inactive records that impact business visibility and outreach effectiveness. The analysis was performed using **Excel for data cleaning** and **Power BI for visualization**, resulting in an interactive dashboard that highlights key data gaps and completeness metrics.

The project simulates a real-world **data analyst workflow**, covering raw data handling, cleaning, validation, modeling, and dashboard storytelling.

---

## 🎯 Project Objective

* Identify missing and incomplete customer profile information
* Measure overall data completeness and profile quality
* Classify profiles as **Complete** or **Incomplete**
* Track **Website Status** (Active / Inactive)
* Provide actionable insights for improving data quality and onboarding processes

---

## 📁 Dataset Description

* Source File: **Uncleaned Excel (.xlsx)**
* Main Sheet: `user_details`
* Supporting Sheets: Contained scattered and missing customer information
* Total Records Analyzed: **747 customer profiles**

### Key Columns:

* Full Name
* Company Name
* Profile Photo
* Email ID
* Contact Number
* Website
* About Company
* Address & Location

---

## 🧹 Data Cleaning & Preparation

The dataset was initially uncleaned and inconsistent. The following steps were performed:

1. Created a **new master sheet** to consolidate all customer data
2. Used **VLOOKUP / XLOOKUP** to merge missing data from supporting sheets
3. Replaced blank and `UNDEFINED` values with **NULL**
4. Standardized the `full_name` column using proper formatting
5. Validated email IDs and contact numbers
6. Manually verified all website URLs
7. Created a derived column:

   * **Website Status** → Active / Inactive
8. Created **Profile Status** column based on key fields:

   * Profile Photo
   * Full Name
   * Email
   * Contact Number
   * Website

---

## 📊 Power BI Dashboard Structure

### 🔹 Page 1: Overview Dashboard

**Title:** Customer Profile Data Quality Dashboard

**KPIs:**

* Total Customers
* Missing Profile Photo
* Missing Company Name
* Missing Website
* Missing About Section
* % Profiles with Missing Data

**Visuals:**

* Donut Chart – Profile Photo Availability
* Bar Chart – Profile Status (Complete vs Incomplete)
* Bar Chart – Missing Fields by Category
* Bar Chart – Website Status (Active vs Inactive)

**Filters / Slicers:**

* Profile Status
* Company Name
* Has Missing Data

---

### 🔹 Page 2: Data Completeness Analysis

**Title:** Data Completeness Analysis

**Visuals:**

* Bar Chart – Top 5 Companies Missing Key Records
* Donut Chart – Overall Profile Completeness
* Table – Customer-level Data Completeness View

**Filters / Slicers:**

* Profile Status
* Company Name
* Primary Address

---

## 📈 Key Insights

* **747 total customer profiles analyzed**
* **71.22% profiles were incomplete**
* Most commonly missing fields:

  1. Profile Photo
  2. About Company
  3. Website
* Nearly **50% of profiles had inactive or missing websites**
* A small number of companies contributed disproportionately to missing data

---

## 💡 Recommendations

* Make **profile photo mandatory** during onboarding
* Introduce **profile completion percentage indicators**
* Send **automated reminders** for incomplete profiles
* Prioritize correction for companies with highest missing data
* Implement **automated website validation checks**

---

## 🛠 Tools & Technologies

* **Microsoft Excel** – Data cleaning & validation
* **Power BI Desktop** – Data modeling & dashboard creation
* **DAX** – Measures and calculated columns

---

## 🧠 Key Skills Demonstrated

* Data Cleaning & Validation
* Excel Lookups (VLOOKUP, XLOOKUP)
* Data Quality Analysis
* Power BI Dashboard Design
* KPI Development
* Business Insight & Storytelling

---

## 📌 Conclusion

This project demonstrates how structured data cleaning and visualization can uncover critical data quality issues. The Power BI dashboard enables stakeholders to monitor profile completeness, improve customer data governance, and drive more effective outreach strategies.

---

## 👤 Author

**Role:** Data Analyst Intern / Aspiring Data Analyst
**Project Type:** Self / Internship-Level Data Analytics Project
