# 🇮🇳 Smart India Hackathon 2026 – Power BI Dashboard

## 📊 Project Overview

This project presents an interactive **Power BI Dashboard** created using the Smart India Hackathon (SIH) 2026 Problem Statements dataset.

The dashboard provides a clear and interactive view of problem statements submitted by different organizations, ministries, and departments.
## 🎯 Dashboard Pages
<img width="1332" height="782" alt="image" src="https://github.com/user-attachments/assets/219e8c2e-d7de-489e-9d7c-286850cece16" />
<img width="1332" height="792" alt="image" src="https://github.com/user-attachments/assets/2ec2b4b8-a33b-4513-85a5-034376e17165" />
<img width="1327" height="785" alt="image" src="https://github.com/user-attachments/assets/e4d06aad-754b-4b84-9dba-750ac871199c" />




## 📌 Dataset Overview

- **Total Problem Statements:** 226
- **Participating Organizations:** 30
- **Themes:** 18
- **Categories:** 2
  - Software
  - Hardware
- **Submitted Ideas:** 0/500 at the time of dataset collection


### 1. 🏠 Home
Provides an introduction to the SIH 2026 dataset and navigation to the dashboard pages.

### 2. 📈 Problem Statement Analysis
Provides visual analysis of:
- Problem Statements by Organization
- Problem Statements by Theme
- Software vs Hardware distribution
- Top 10 Organizations
- Interactive filters

### 3. 🔎 Problem Statement Explorer
Allows users to explore individual problem statements using filters such as:
- Organization
- Category
- Theme
- Deadline

## 🛠️ Tools & Technologies

- Microsoft Power BI
- DAX
- Microsoft Excel
- Data Cleaning
- Data Visualization

## 📊 Key Features

- Interactive dashboard
- Dynamic filters and slicers
- Organization-wise analysis
- Theme-wise analysis
- Category distribution
- Top 10 organization analysis
- Problem statement explorer
- Deadline-based filtering

## 📂 Dataset Columns

- S.No.
- Organization
- Problem Statement Title
- Category
- PS Number
- Submitted Idea(s) Count
- Theme
- Deadline for Idea Submission

## 📈 DAX Measures

```DAX
Total PS =
COUNTROWS(PS_Data)
