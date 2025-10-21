# Amazon-data-analysis-Project(interactive creation using Power bi)
## Project objective
This project involves the analysis of Amazon sales and delivery data visualized in a dashboard format, likely built using Power BI. The dashboard provides a high-level overview of key operational and sales metrics, enabling stakeholders to monitor performance, identify trends, and make data-driven decisions regarding sales, logistics, and geographic performance. The primary objective is to gain insights into sales efficiency, delivery performance, and geographical distribution of sales.
## Dataset used  
-<a href="https://github.com/anasmummar-702/Data-analysis-dashboards/blob/main/Amazon%20Data.xlsx">Amazon Data</a>
## Questtions(KPIs)

-What is the growth rate (MoM/YoY) of the $11.67M Sales Amount?

-Which specific products within the Top 5 Categories are the primary revenue drivers?

-What is the average time-to-delivery for orders, broken down by each Delivery Partner?

-What is the precise fulfillment success percentage, and how does it benchmark against industry standards?

-How much does the highest-contributing ship-state account for as a percentage of the total sales?

-What is the volume, and what are the root causes, for orders categorized with an concerning Courier Status (e.g., 'Delayed' or 'Exception')?

-What is the Average Order Value (AOV) when segmented by the Top 5 Category?

-Which of the Top 10 States yields the highest gross profit margin (assuming profit data exists)?

-How do the sales amount and fulfillment rates differ between B2B and B2C transactions?

-What is the performance variance (Sales & fulfillment) across different Sales Channels?

## Dashboard intractions 
-<a href="https://github.com/anasmummar-702/Data-analysis-dashboards/blob/main/Screenshot%202025-10-21%20162433.png">View Dashboard</a>

## Process

### Data Acquisition & Connection:

Identify and connect to the raw data sources (e.g., Amazon sales logs, fulfillment tables, delivery tracking data).

Step: Connect Power BI to the underlying data source(s).

### Data Cleaning & Transformation (ETL):

Clean the data (e.g., handle missing values, correct data types, remove duplicates).

Transform the data (e.g., create calculated columns or measures like the total "Sales Amount").

Step: Use Power Query Editor to shape and refine the raw data.

### Data Modeling & Relationships:

Establish relationships between different data tables (e.g., Sales table linked to Fulfillment table by Order ID).

Step: Use the 'Manage relationships' and 'Modeling' tools to create a robust data model.

### Measure and Calculation Creation:

Develop the necessary calculated fields or measures (e.g., Total Sales, fulfillment rates, top categories) using DAX (Data Analysis Expressions).

Step: Use the 'New measure' and 'New column' features under the 'Home' or 'Modeling' tabs.

### Visualization Design & Dashboard Creation:

Select appropriate visualization types (bar charts, donut charts, KPI cards) to represent the KPIs effectively.

Build the dashboard layout, applying a consistent design theme (e.g., the dark blue theme seen in the image).

Step: Drag and drop fields onto the canvas and select visualization types from the 'Visualizations' pane.

## Dashboard
<img width="513" height="665" alt="Screenshot 2025-10-21 175141" src="https://github.com/user-attachments/assets/eb9d59f8-6a35-42c2-abf3-bbdd297e5cb3" />


## Insights
-Sales Concentration: Sales are heavily concentrated both by product (Top 5 Category) and geography (Top 10 States), indicating clear high-leverage areas for investment.

-Logistics Complexity: Management requires continuous monitoring of multiple Delivery Partner SLAs to maintain delivery quality and optimize costs.

-Operational Health: The high Sales Amount ($11.67M) combined with the status of Fulfillment and Courier Status metrics provides an immediate health check on the supply chain.


## Conclution
The Amazon Analysis Dashboard is a successful implementation of a data-to-insight tool. It delivers a clear, centralized view of sales and operational performance. The immediate actionable takeaway is the need for a dual focus: optimizing inventory and marketing for the Top 5 Categories while streamlining logistics to better serve the Top 10 States. This dashboard is a critical asset for ongoing performance monitoring and strategic decision-making
