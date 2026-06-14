# 📊 Insurance Premium & Claims Analytics: End-to-End Data Pipeline

## 📌 Project Overview

This project is an end-to-end data analytics solution designed to track, analyze, and visualize insurance premiums, claims processing, and customer satisfaction. The pipeline extracts raw transactional and customer data from **MS SQL Server**, transforms it, and feeds it into highly interactive **Power BI** dashboards.

Beyond standard financial reporting, this project incorporates **NLP-driven Sentiment Analysis** on customer feedback to categorize user experiences, helping stakeholders identify service gaps and operational bottlenecks. The final solution is deployed via **Power BI Service (Fabric)** with automated data refreshes and strict data governance.

## 💡 Key Business Questions Answered

This dashboard empowers insurance executives and operational managers to answer critical business questions at a glance:

### Financial & Operational Metrics

-   **Revenue Generation:** Which policy types (Travel, Health, Auto, Life, Home) are driving the highest premium amounts?
    
-   **Claims Liability:** What is the total financial exposure across active coverage amounts versus actual claim amounts?
    
-   **Processing Efficiency:** What is the current volume of claims categorized by their processing status (Settled, Rejected, Pending)?
    
-   **Financial Bottlenecks:** What is the exact monetary value of _pending_ claims currently sitting in the pipeline across different policy types?
    

### Demographic Insights

-   **Risk by Age:** How do claim amounts correlate with different age groups (Elder, Adult, Young Adult), and which demographic poses the highest financial risk?
    
-   **Customer Retention:** What is the ratio of active versus inactive policies, providing a clear view of customer churn?
    

### Customer Experience & Sentiment

-   **Overall Satisfaction:** What proportion of the customer base rates the service as "Excellent" versus "Needs Improvement"?
    
-   **Pain Points:** What are the most recurring keywords in negative feedback (e.g., "confusing policies," "long wait times," "website down")?
    
-   **Service Evaluation:** How do individual sentiment scores correlate with specific customer feedback narratives?

## 🚀 Key Technical Implementations

-   **End-to-End Pipeline architecture:** Engineered a seamless flow from a relational database (SQL Server) to a cloud-based reporting environment.
    
-   **Sentiment Analysis:** Processed raw customer feedback into quantifiable sentiment scores, categorizing them into _Excellent_, _Good_, and _Needs Improvement_.
    
-   **Row-Level Security (RLS):** Implemented strict data governance, ensuring that end-users only access the data relevant to their specific role, department, or region.
    
-   **Automated Scheduled Refresh:** Configured data refresh schedules within Power BI Service to ensure stakeholders always have access to real-time insights without manual intervention.
    
-   **Advanced DAX & Data Modeling:** Built dynamic measures for multi-million dollar KPIs (Premium, Coverage, and Claim amounts) and established robust relational models between policies, claims, and customer demographics.
        

## 🏗️ System Architecture & Workflow

1.  **Data Storage & Extraction:** Relational tables (Policies, Claims, Customers, Feedback) stored and queried in **MS SQL Server**.
    
2.  **Data Processing & Modeling:** Data imported into **Power BI Desktop** using DirectQuery/Import modes. Star schema designed for optimized filtering and DAX calculations.
    
3.  **Advanced Analytics:** Text analytics applied to qualitative feedback columns to generate numeric sentiment scores and category bins.
    
4.  **Visualization:** Development of multi-page interactive dashboards with drill-down capabilities, tooltips, and dynamic slicers.
    
5.  **Deployment:** Published to **Power BI Service (Fabric)**.
    
6.  **Maintenance:** Established Row-Level Security roles and automated schedule refreshes to keep the operational dashboard fully automated.
    

## 📸 Dashboard Previews

### 1. Executive Summary & Claims Analytics

<img width="1387" height="759" alt="Screenshot 2026-06-12 215805" src="https://github.com/user-attachments/assets/939c27bb-c9fe-43f3-bb5c-1543942d5cca" />


### 2. Customer Sentiment & Feedback Analysis

<img width="1318" height="781" alt="Screenshot 2026-06-12 215547" src="https://github.com/user-attachments/assets/899824ed-65b2-4056-a161-631869586216" />


### 3. Raw Data & Granular View

<img width="1377" height="750" alt="Screenshot 2026-06-12 215819" src="https://github.com/user-attachments/assets/9bc32a5b-8198-43b3-bc85-c4b094f3fb50" />


## 🛠️ Skills Demonstrated

-   **Database Management:** MS SQL Server, Data Extraction, Relational Databases
    
-   **Business Intelligence:** Power BI Desktop, Power BI Service, DAX, Data Modeling
    
-   **Data Engineering:** Automated Pipelines, Scheduled Refreshes, Row-Level Security (RLS)
    
-   **Advanced Analytics:** Sentiment Analysis, Text Mining, KPI Development
    

**Author:** Venkat Yalamanchili

**Contact:** [yalamanchilivenkat56@gmail.com]
