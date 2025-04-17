# Excel---Data Bootcamp---Workbook
 
![Excel](https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

This workbook is a compilation of practical exercises, notes, and guided tasks completed as part of Week 1 in the Data Technician course. It focuses on foundational data concepts, Excel-based analysis, and understanding key regulations around data handling.

## 📅 Weekly Breakdown

### ✅ Day 1: Data Legislation
**Overview of UK data laws and regulations:**
- **Data Protection Act**
- **GDPR**
- **Freedom of Information Act**
- **Computer Misuse Act**

For each regulation: defined its purpose, impact on data work, and real-world application examples.

### ✅ Day 2: Excel Data Tasks
#### Task 1:
- Created a structured **Excel Table** using `retail-sales_dataset.xlsx`.
- Using the **filter** function, filter ‘Age’ to ‘largest to smallest’ 
- Using the **SUM** function, show me the commission total in cell ‘P10’ 
- Using the **AVERAGE** function, show me the average commission in cell ‘P11’ 
  
#### Visuals:
![Screenshot 2025-03-08 234452](https://github.com/user-attachments/assets/a1ffc09a-72a1-4890-beab-8fa2f9035410)
![Screenshot 2025-03-08 235005](https://github.com/user-attachments/assets/84aef692-5825-43b3-a044-b37b5a5d9e86)
![Screenshot 2025-03-09 001041](https://github.com/user-attachments/assets/d09dfd2c-f510-4a74-b250-8ee88b5967fc)
![Screenshot 2025-03-09 001146](https://github.com/user-attachments/assets/e93964fb-9fd0-4221-9cfa-15b46f545277)

#### Task 2:
- Further tasks with Excel data using filters and data manipulation (screenshots included).

### ✅ Day 3: Pivot Tables & Categorisation
#### Task 1: Bike Sales Pivot Table
- Explored Excel pivot tables with bike sales data.
- Identified market distribution and profitability insights
![Screenshot 2025-03-09 203020](https://github.com/user-attachments/assets/a204fec8-7521-481a-b2ec-9360f907bdf3)

Generating insights:
#### What country has sales in all markets? 
- Australia and United Kingdom have sales in all markets. 
![Screenshot 2025-03-09 162556](https://github.com/user-attachments/assets/992a713b-b98a-428c-969e-728276b6e8b6)
- The most profitable age group are the adults (35-64).

#### What are the most profitable markets by country, age group, and gender? 
![Screenshot 2025-03-09 203623](https://github.com/user-attachments/assets/9930be94-e18d-4404-95fe-30c201acd667)
![image](https://github.com/user-attachments/assets/f3f135ed-8cc0-47df-8811-cf9d1f0c9771)

- The most profitable markets (by the number of orders) are the Female young adult (25-34) and the adults (35-64) groups in Australia and the Adult Females and Adult Male groups in the United States.


- Firstly, the table contains a multitude of missing values.  

When analysing each country’s profit margins, we can see that   United States has the highest total sales but also a high profit margin. Thus, it may be the most profitable market overall. 

Also, the female customers are the most profitable group due to higher profit margins, this suggests that the U.S. market is a strong performer in terms of profitability, particularly for older females (600.37%) and males (408.80%) and younger females (270.94%). Another strong market for the same gender/age groups is the Australian one. 

Also, some other remarks: 

-United Kingdom shows some promise in the Male Adults (35-64) age group with high profit margins (136.31%) and low order quantities. This indicates that more premium products are sold there. At the same time for the in the Female Young Adult age group, for the same quantity of products sold as before, the profit margin is almost 4 times smaller. This indicating that in these markets, the company may need to reconsider its pricing strategy, improve marketing efforts, or evaluate the type of bikes sold. 

-France on the other hand has the same problem as UK, but in the male Youth age group, as profit margins are low compared to the number of items sold. This indicates that the items sold are lower priced. 
#### Task 2: Regional Sales Analysis
- Built a pivot table summarising product sales by county.
- Used **SWITCH** function to categorise sales volumes:
    - **High** (> 600)
    - **Medium** (300–600)
    - **Low** (< 300)

#### Task 3: Visualisations Lab
- Created Excel charts based on bike sales visualisation dataset.
- Focused on exploring Excel's visualisation capabilities.

## 🛠 Tools Used
- **Microsoft Excel**
- Retail & sales datasets (provided with the workbook)

## 📂 Structure
This repository contains:
- **Data_Technician_Workbook_Week1.docx** – Main workbook with tasks and screenshots
 [Data_Technician_Workbook_Week1.docx](https://github.com/user-attachments/files/19800816/Data_Technician_Workbook_Week1.docx)
- Folder for Excel files used in analysis


