# ⚓ NIMASA ICT Inventory & Resource Allocation Analysis

**Note:** This project showcases an MIS prototype I developed during my internship. The dataset is modified for privacy, but the logic, formulas, and dashboard reflect the real solution I delivered.

## 1. Executive Summary
During my ICT internship at the **Nigerian Maritime Administration and Safety Agency (NIMASA)**, I developed a Management Information System (MIS) to automate the tracking of hardware requests. 

By transforming a fragmented manual log into a centralized Excel dashboard, I provided the department with a clear view of resource distribution, enabling data-driven procurement and inventory management.

## 2. Project Overview
This project focuses on managing ICT equipment across its full lifecycle within NIMASA — from request to final allocation.

It helps track key categories like power supply, imaging devices, and computing hardware, while giving stakeholders better visibility into inventory and resource distribution.

## 3. Data Source
The dataset was collected manually by interns at NIMASA using physical records and later digitized into Microsoft Excel for analysis.

It contains 234 rows and 7 columns, including key fields such as Department, Requested Items, Category, Serial Number, and Description.

This is transactional data, where each row represents a hardware request and its allocation to a department.

Some limitations include possible human errors from manual entry and a limited scope within the internship period.

## 4. Problem Statement
The NIMASA ICT department managed hardware requests using paper-based records, which reduced efficiency and made it difficult to track inventory and resource usage.

This was important because it led to delays in fulfilling requests and reduced the accuracy of procurement decisions due to a lack of clear, centralised data.

To address this, the project focused on answering key questions such as:

* Which hardware categories are most in demand?

* Which departments request the most ICT resources?

* Where are there gaps between requested and allocated items?

* What insights can guide better procurement planning?

## 5. Tools & Methodology
**Tool Used:** Microsoft Excel

**1. Data Collection**

Data was collected manually from staff across a NIMASA branch and recorded for analysis.

**2. Data Cleaning & Preparation**

To improve data quality and reliability, the following steps were performed:

* Removing duplicate records

* Handling missing values

* Correcting inconsistent data entries and formats

* Standardizing department names and item categories

These steps ensured consistency and reduced the risk of inaccurate insights.

**3. Data Transformation & Processing**

Pivot Tables were used to aggregate and summarize request data, while functions like XLOOKUP/VLOOKUP supported efficient data retrieval.

**4. Data Validation**

Cross-checks were conducted to ensure:

* KPI outputs remained consistent across filters and segments

**5. Data Visualization**

An interactive dashboard was developed to answer key stakeholder questions, including:

* Total number of items

* Most requested item

* Least requested item

* Top 5 requested items

* Most requested items by category

* Requests by department

* Requests by department and category


## 6. Exploratory Data Analysis (EDA)

This dataset represents a single snapshot of ICT requests, so the analysis focused on understanding request distribution and category patterns rather than trends over time.

**Key Insights**

* Identified high-demand categories such as Computing and Power Supply, which make up a significant portion of total requests

* Analyzed item descriptions to distinguish between low-value accessories (e.g., Printer) and high-value equipment (e.g., Monitor)

**Distribution Analysis**

* Examined request volume across departments to identify the highest consumers of ICT resources

* Analyzed the spread of requests across categories to understand whether demand is more focused on office tools.

## 7. Key Insights
* **Primary Demand:** Computers and Power Supply units represent the highest volume of requests across the agency.
* **Departmental Leaders:** Identified the top-consuming departments, allowing for targeted technical support.
* **Inventory Balance:** Discovered a disparity between the "Least Requested" and "Most Requested" items, suggesting a need to rebalance stock levels.

## 8. Visuals/Dashboard Preview
The dashboard features a professional UI including:
* **KPI Cards:** Total Equipment Count and Most Requested Item.
* **Bar Charts:** Equipment breakdown by Department.
* **Slicers:** Interactive filters for Category and Departmental views.

### Visual 1: ICT Equipment Inventory Dashboard 
<img width="300" height="387" alt="image" src="https://github.com/user-attachments/assets/00a4026b-72d5-40ee-b7d1-81df5b09255a" />

### Visual 2: Top 5 Requested ICT Equipment 

<img width="169" height="212" alt="Screenshot 2026-03-17 170859" src="https://github.com/user-attachments/assets/58d13a8f-606f-42f4-a2c0-618ce01a2fc2" />


### Visual 3: Requested ICT Equipment by Department 

<img width="416" height="241" alt="image" src="https://github.com/user-attachments/assets/7fb7cb25-833b-49ae-bb62-f089a6444abc" />


### Visual 4: Requested ICT Equipment by Department and Category

<img width="651" height="237" alt="image" src="https://github.com/user-attachments/assets/0c31436b-f83b-40bb-a32a-429d42e7fbd1" />


## 9. Recommendations

**1. Implement Proactive Infrastructure Audits**

Conduct electrical audits in departments with high Power Supply requests (e.g., UPS, inverters). Frequent requests may indicate underlying power issues, so addressing infrastructure can reduce repeated hardware damage and lower long-term costs.

**2. Establish Data-Driven Procurement Thresholds**

Set minimum stock level alerts for high-demand categories like Computing and Imaging. This supports proactive purchasing and helps prevent stock shortages of critical equipment.

**3. Provide Targeted User Training**

Organize basic hardware care training for departments with frequent requests. This can reduce damage caused by improper usage and extend the lifespan of ICT equipment.

**4. Transition to a SQL-Based System**

Upgrade from Excel to a SQL-based asset management system for real-time tracking. This will reduce manual data entry, improve accuracy, and support better decision-making.

## 10. Limitations

* Data is static (Excel-based) and requires manual updates

* Small dataset (234 records), may not reflect long-term trends

* Some requests were made on behalf of departments, not individuals

* Data is limited to one NIMASA branch

* Assumes all recorded requests were fulfilled

* Possible errors from manual data entry

## 11. Implementation

This dashboard was presented to ICT supervisors as a secondary verification tool for monthly inventory audits. Below is the strategic roadmap for transitioning this prototype into a permanent agency system.

**Recommendation: Transition to a SQL-Integrated MIS**

**What:** 
Move from Excel to a centralized SQL database with a Power BI dashboard to enable real-time tracking and reduce manual data entry.

**Who:**

-Owner: ICT Manager

-Support: Data Analyst Interns

-Approval: Director of ICT

**Timeline:**

Month 1: Design database and migrate existing data

Month 2: Test system with one department

Month 3: Full rollout across the agency

**Success Metrics:**

-Eliminate manual data entry errors

-Real-time visibility of inventory

-Faster request fulfillment

**Resources Needed:**
SQL Server, Power BI licenses, and regular system maintenance

**Risks & Mitigation:**

- Risk: Low digital adoption by staff

- Mitigation: Provide training and a simple user guide


## 12. Conclusion
This project addressed inefficiencies in NIMASA’s paper-based system by analyzing hardware request data and identifying key demand patterns, especially in Computing and Power Supply.

The resulting dashboard improves visibility, supports better decision-making, and enhances resource allocation.

Overall, the project demonstrates how transforming raw data into insights can drive more efficient operations and smarter procurement decisions. 
