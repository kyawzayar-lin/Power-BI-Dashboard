# 📶 ISP Operations & Performance Dashboard


## 📌 Project Overview
This repository contains a **Power BI Dashboard** designed to analyze operational data for a Fiber-to-the-Home (FTTH) Internet Service Provider. The project focuses on tracking the lifecycle of service orders—from initial installation to ongoing maintenance—while evaluating technical team efficiency.

The goal of this practice project was to transform raw ISP datasets into actionable insights regarding customer growth, service bottlenecks, and workforce performance.

---




## 📂 Project Resources
* 📄 [Download PDF Version (PDF)](Myanmar Citizen Dashboard.pdf)
* 🐍 [View Data Pre-processing Script](PBIX_File/Myanmar Citizen Dashboard.pbix)
* 📊 [Raw Dataset](data/Test_Data.xlsx)


## 📊 Key Features & Insights

### 1. Installation Lifecycle Tracking
Monitors the flow of new customer acquisitions by categorizing installation orders:
* **Total Customer Counts:** Tracking overall growth and network footprint.
* **Order Status:** Real-time breakdown of **Completed**, **Pending**, and **Canceled** installations.
* **Success Rate:** Analysis of successful installs vs. cancellations to identify gaps between sales and technical fulfillment.

### 2. Maintenance & Service Reliability
* **Maintenance Volume:** Tracking the frequency and types of reported service tickets.
* **Resolution Metrics:** Categorization of maintenance tasks into **Completed**, **Pending**, or **Canceled** status.

### 3. Efficiency & Lead Time
* **Installation Completion Time:** Measures the average duration from order placement to "Light-on" (Active status).
* **SLA Compliance:** Visualizing whether the technical team is meeting promised service timelines.

### 4. Team Performance Analytics
* **Technician Productivity:** Comparative analysis of performance across different field teams.
* **Task Distribution:** Load balancing analysis (Installations vs. Maintenance tasks per team).
* **Completion Ratios:** Identifying high-performing units and teams requiring additional support.

---

## 🛠️ Tools Used
| Tool | Purpose |
| :--- | :--- |
| **Power BI Desktop** | Primary tool for data modeling and dashboard visualization. |
| **Power Query** | Data cleaning, handling null values, and ETL processes. |
| **DAX** | Used to create calculated measures for SLA and Completion rates. |

---

## 📂 Dataset Description
The analysis is based on a simulated ISP dataset (FTTH focused) containing the following attributes:

* **Order IDs:** Unique identifiers for every service task.
* **Timestamps:** Tracking Request, Dispatch, and Completion dates.
* **Task Type:** Categorized as `Installation` or `Maintenance`.
* **Status:** Current state of the ticket (Complete/Pending/Cancel).
* **Team ID:** The specific field unit assigned to the task.
