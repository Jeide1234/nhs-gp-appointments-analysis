# nhs-gp-appointments-analysis
Excel and Power Query project analysing NHS GP appointment attendance, missed appointment patterns, and healthcare data quality issues.

# 🏥 NHS GP Appointments Data Cleaning & Missed Appointment Analysis

## 🏢 Business Problem

Missed GP appointments can negatively impact healthcare operations by increasing scheduling inefficiencies, reducing patient access to care, and affecting resource planning.

In addition, poor data quality such as missing values, inconsistent formatting, and incomplete records can reduce the reliability of healthcare reporting and operational analysis.

This project focuses on analysing NHS GP appointment data to identify missed appointment patterns, assess data quality issues, and demonstrate how data cleaning improves the accuracy of operational reporting.

---

## 🎯 Project Objective

The objective of this project was to clean and analyse NHS GP appointment data using Excel and Power Query in order to:

- Assess appointment attendance patterns
- Identify trends in missed appointments
- Evaluate operational data quality issues
- Improve data consistency and reporting accuracy
- Generate actionable operational insights

---

## 📁 Dataset Information

The dataset contains anonymised NHS GP appointment records.

It consists of:
- 100 rows
- 10 columns

### Key Fields Included:
- Patient_ID
- Appointment_Date
- Appointment_Time
- Appointment_Type
- Doctor_Name
- Appointment_Status
- Notes

---

## ⚠️ Data Quality Issues Identified

Several data quality problems were identified before cleaning, including:

- Missing Patient_ID values
- Blank Appointment_Time fields
- Blank Appointment_Type values
- Missing Notes entries
- Inconsistent date formatting
- Inconsistent appointment status naming
- Inconsistent doctor name formatting

These issues affected reporting accuracy and operational analysis reliability.

---

## 🧹 Cleaning Process

### Excel & Power Query Cleaning Steps

- Standardized Appointment_Date format
- Converted Appointment_Time to 24-hour format
- Cleaned text fields using TRIM() and PROPER()
- Standardized Doctor_Name formatting
- Standardized Appointment_Status categories
- Replaced missing values where necessary
- Removed Patient_ID suffix inconsistencies
- Created helper columns for analysis

### New Columns Created
- Appointment_Hour
- Missing_Time_Flag
- Missed_Appointment

---

## 📊 Analysis & Insights

### 1. Missed Appointments by Time of Day
- 9 AM appointments recorded the highest missed appointment rate (67%).
- Early morning appointments appear more vulnerable to patient non-attendance.

### 2. Missed Appointments by Appointment Type
- Emergency-labelled appointments showed the highest missed rate (48%).
- Follow-up appointments recorded the highest appointment volume.

### 3. Operational Data Quality
- Missing appointment times reduced the reliability of time-based analysis before cleaning.
- Standardizing status values improved attendance reporting consistency.

---

## 💡 Recommendations

### 1. Improve Early-Morning Attendance
Implement appointment reminders for early-morning bookings to reduce missed appointments.

### 2. Review Emergency Appointment Classification
Investigate whether emergency appointments are being categorized correctly.

### 3. Strengthen Data Quality Processes
Introduce validation rules for appointment time, status, and doctor naming consistency.

### 4. Improve Operational Reporting
Use standardized data cleaning processes to improve healthcare reporting reliability and decision-making.

---

## 🛠️ Tools Used

- Microsoft Excel
- Power Query
- Pivot Tables
- Data Cleaning
- Operational Analysis
- Data Visualization

---

## 🧠 Skills Demonstrated

- Data Cleaning
- Data Quality Assessment
- Excel Analytics
- Power Query Transformation
- Healthcare Data Analysis
- Operational Reporting
- Pivot Table Analysis
- Data Visualization
- Analytical Storytelling

---

## 📂 Repository Structure

- Excel Analysis File
- Presentation Slides
- Project Screenshot
- README Documentation

---

##(Screenshot/NHS GP Appointments Dataset_Data Cleaning_Quality Report.png)

---

## ✅ Final Conclusion

This project demonstrates how Excel and Power Query can be used to improve healthcare operational reporting through effective data cleaning and analytical reporting.

By identifying data quality issues and analysing missed appointment patterns, the project provides insights that can support better scheduling efficiency, operational planning, and healthcare decision-making.
