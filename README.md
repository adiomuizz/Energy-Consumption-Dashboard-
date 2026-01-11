# Energy-Consumption-Dashboard
This dashboard provides a comprehensive look at utility performance, focusing on the relationship between energy distribution and financial recovery.

<h1> Operational Excellence: Energy & Billing Analysis</h1>
<h2> 📌 Project Overview </h2>

This project involves the development of a performance monitoring dashboard for a utility provider. It tracks key metrics across different Business Units (Ikeja, Oshodi, Ikorodu) and customer service bands to evaluate energy distribution efficiency and revenue collection performance.


The primary goal is to provide stakeholders with actionable insights into Collection Efficiency (CE) and energy consumption patterns across various feeders and customer segments.

<h1> 📊 Key Performance Indicators (KPIs)</h1>
The dashboard tracks five high-level metrics to gauge overall operational health:

| Metric               | Value   | Description                                                                 |
|----------------------|---------|-----------------------------------------------------------------------------|
| Amount Billed        | 10.62M  | Total monetary value invoiced to customers.                                |
| Energy Billed (kWh)  | 39.24K  | Total energy consumption recorded for billing.                             |
| Total Amount Paid    | 6.45M   | Total revenue actually collected from customers.                           |
| CE (%)               | 164.84% | Collection Efficiency (>100% suggests recovery of arrears or past debts).  |
| Average Billing      | 265.61K | Mean bill amount across the customer base.                                 |


<h2> 🔍 Data Interpretations </h2>
1. <strong>Energy Distribution by Feeder</strong>

The bar-and-line chart illustrates energy consumption across 10 specific feeders.

- Top Performer: Feeder 1 has the highest energy consumption (~7k kWh).

- Trend: There is a steady decline in energy distribution from Feeder 1 through Feeder 9, indicating varying demand densities across the network.

2. <strong>Feeder Performance Matrix</strong>
   
The table on the right uses a Traffic Light (RAG) system to evaluate feeder health:

- CE (%) Status: Most feeders (1, 10, 2, 3, 4) show a "Red Diamond," likely indicating that while the aggregate CE is high, these specific feeders may have high volatility or specific collection targets unmet.

- MoM Energy Change: Most feeders show a negative trend (indicated by green circles and red diamonds), suggesting a month-over-month decrease in energy throughput.

3. <strong>Segmented Analysis (Customer Type)</strong>

The bottom table breaks down the data by Commercial, Industrial, and Residential sectors:

- Revenue Driver: The Industrial sector is the largest contributor, with a Total Amount Bill of 4.78M (nearly 45% of total billing) despite having only 20 customers.

- Efficiency: Residential customers have the highest "Average Energy Per Customer" (1,141.32 kWh), suggesting high individual usage compared to the other segments.

- Growth: Energy consumption has increased across all segments compared to "Energy Last Month" (e.g., Industrial moved from 12.6k to 15.1k kWh).


<h2> 🛠 Tech Stack </h2>

Data Visualization: Power BI (indicated by the slicer and card styles).

Data Source: Excel

Analysis Focus: Revenue Assurance, Energy Accounting, and Utility Operations.

<h2> 💡 Recommendations </h2> 

<strong>Investigate CE > 100%:</strong> Analyze if the high collection efficiency is due to aggressive debt recovery or potential data entry errors in the "Total Amount Paid" field.

<strong>Focus on Industrial Segment:</strong> Given that 20 industrial customers generate nearly half the revenue, personalized account management for this group is critical for financial stability.

<strong>Feeder Optimization:</strong> Feeder 1 handles significantly more load than Feeder 9. A technical audit could determine if load balancing is required to prevent equipment fatigue.

🖼️ Screenshots

<img width="925" height="532" alt="image" src="https://github.com/user-attachments/assets/cbe6cec9-71bc-4b52-a3db-63026f9a8d56" />

🌐 Online Report: You can view and interact with the live version of the Dashboard here

🔗 [View Power BI Dashboard](https://app.powerbi.com/view?r=eyJrIjoiZGU5NGFmZTgtNzIxMC00YWUwLWEyNTEtOTNhNDE4NzEzYTJmIiwidCI6IjU4MTgxNmIyLWMwYmUtNGVhYS04MGUzLTI5ZTVmMjQ4NjQ5NCIsImMiOjh9)






