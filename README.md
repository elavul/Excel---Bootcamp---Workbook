# 📊 Excel---Data Bootcamp---Workbook
 
![Excel](https://img.shields.io/badge/-Excel-217346?style=for-the-badge&logo=microsoft-excel&logoColor=white)

This workbook is a compilation of practical exercises, notes, and guided tasks completed as part of Week 1 in the Data Technician course. It focuses on foundational data concepts, Excel-based analysis, and understanding key regulations around data handling.

----- 
## 🧠 Weekly Breakdown


### ✅ Day 1: Data Legislation
**Overview of UK data laws and regulations:**
- **Data Protection Act**
- **GDPR**
- **Freedom of Information Act**
- **Computer Misuse Act**
  
For each regulation: defined its purpose, impact on data work, and real-world application examples.

----- 
### ✅ Day 2: Excel Data Tasks

#### Day 2 - Task 1 - Retail Sales Data Analysis
This project focuses on exploring and analyzing retail customer transaction data using Microsoft Excel.
##### Tasks included:
- Import a csv file into Excel, perform Data Cleaning and Structuring
- Transform the Master data into a table 
- Using the **filter** function, filter ‘Age’ to ‘largest to smallest’ 
- Using the **SUM** function, show me the commission total in cell ‘P10’ 
- Using the **AVERAGE** function, show me the average commission in cell ‘P11’ 
  
##### 📂Let's explore the dataset:
<img src="https://github.com/user-attachments/assets/a1ffc09a-72a1-4890-beab-8fa2f9035410" width="400" />
<img src="https://github.com/user-attachments/assets/84aef692-5825-43b3-a044-b37b5a5d9e86" width="400" />
<img src="https://github.com/user-attachments/assets/d09dfd2c-f510-4a74-b250-8ee88b5967fc" width="400" />
<img src="https://github.com/user-attachments/assets/e93964fb-9fd0-4221-9cfa-15b46f545277" width="400" />

----- 
#### Day 2 - Task 2:
- Further tasks with Excel data using filters and data manipulation (screenshots included).
----- 
### ✅ Day 3: Pivot Tables & Categorisation

#### Day 3 - Task 1: Bike Sales Pivot Table

- Explored Excel pivot tables using the **bike sales dataset**.
- Created pivot tables to analyze:
  - Market demographics
  - Customer behavior
  - Sales trends by **country**, **age group**, and **gender**
- Identified key insights on **market distribution** and **profitability**.

---

### 🔍 Generating Insights

#### 📌 Insight 1: What country has sales in all markets?

- **Australia** and the **United Kingdom** have sales across **all markets**.
- The most **profitable age group** is **Adults (35–64)**.

<img src="https://github.com/user-attachments/assets/992a713b-b98a-428c-969e-728276b6e8b6" width="400" />

---

#### 📌 Insight 2: What are the most profitable markets by country, age group, and gender?

<img src="https://github.com/user-attachments/assets/9930be94-e18d-4404-95fe-30c201acd667" width="400" />
<img src="https://github.com/user-attachments/assets/f3f135ed-8cc0-47df-8811-cf9d1f0c9771" width="400" />

##### Key Findings:

- The most profitable customer segments (by number of orders and profit margin) include:
  - **Female Young Adults (25–34)** in **Australia**
  - **Adult Females and Adult Males (35–64)** in the **United States**
- The **United States**:
  - Has the **highest total sales**.
  - Shows strong profitability, especially among:
    - Older Females: **600.37%**
    - Older Males: **408.80%**
    - Younger Females: **270.94%**
  - Overall, the **U.S. is the most profitable market**, especially for older demographics and female customers.

---

### ⚠️ Additional Observations & Recommendations

- The dataset includes a **significant number of missing values**, which may impact the reliability of the analysis and require data cleaning before deeper insights can be confidently drawn.

- **Australia**:
  - Shows similarly strong performance among the same gender and age groups, making it another **key market** for targeting high-value segments.

- **United Kingdom**:
  - Strong performance in **Male Adults (35–64)** with **high profit margins (136.31%)** but **low order quantity**.
    - This suggests **premium product sales**.
    - **Female Young Adults** show similar order quantity but **much lower margins**, suggesting:
      - Re-evaluate its **pricing strategy**
      - Enhance **marketing efforts**
      - Consider whether the **product mix** is well suited to this segment

- **France**:
  - Faces similar challenges to the UK
  - Profit margins are **low for Male Youth**, despite high number of units sold.
    - Indicates lower-priced items dominate sales.
    - Suggests a potential need to:
      - Improve pricing strategy
      - Increase value per sale
      - Explore different product offerings for this group

----- 
#### Day 3 - Task 2: 
- Built a pivot table summarising sales by product and county.
- Used **SWITCH** function to categorise sales volumes:
    - **High** (> 600)
    - **Medium** (300–600)
    - **Low** (< 300)
      
- SWITCH Function Example: 
=SWITCH(TRUE, C2 > 600, "High", C2 >= 300, "Medium", "Low")
<img src="https://github.com/user-attachments/assets/13f460c5-1071-4879-80a7-c304e5f7f1e5" width="400" style="margin: 10px 0;" />
<img src="https://github.com/user-attachments/assets/a1fdf423-ae52-4dc1-97b0-afb3ca11cdad" width="400" style="margin: 10px 0;" />

----- 
#### Day 3 - Task 3: Bike_Sales_Visualisations_Lab.xlsx
- Created Excel charts based on bike sales visualisation dataset.
- Focused on exploring Excel's visualisation capabilities.
----- 
## 🧰 Tools Used
- **Microsoft Excel**
- Retail & sales datasets (provided with the workbook)
----- 
## 📂 Structure
This repository contains:
- **Data_Technician_Workbook_Week1.docx** – Main workbook with tasks and screenshots
 [Data_Technician_Workbook_Week1.docx](https://github.com/user-attachments/files/19800816/Data_Technician_Workbook_Week1.docx)
- Folder for Excel files used in analysis
----- 

