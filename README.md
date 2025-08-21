# Data-Analysis-Dashboard-Insurance-Claims

## Project Objective
To conduct a forensic audit analysis of ShieldGruppe's data to identify, validate, and visualize financial relationships and claims involving Sword AG, applying professional skepticism to ensure data integrity and support a presentation to management.

## Dataset
<a href="https://github.com/Luheto/Data-Analysis-Dashboard-Insurance-Claims/blob/main/Data_ShieldGruppe_Claims%20and%20Contracts.xlsx">Data_ShieldGruppe_Claims and Contracts</a>

## Questions This Project Was Solving
- What is the total financial volume (payment amount) and number of claims between ShieldGruppe and Sword AG?

- How have these claims and payments trended over the years? Are there any unusual spikes?

- What is the average value of a claim, and how does it compare across different companies or segments?

- Which underwriters are most associated with these claims, and what is their financial exposure?

- Are there any anomalies or outliers in the data that require further investigative scrutiny?
- Dashboard <a href="https://github.com/Luheto/Data-Analysis-Dashboard-Insurance-Claims/blob/main/Insurance%20Claims.png">Insurance Claims Dashboard</a>
## Steps Taken
- Data Acquisition & Understanding: Received and reviewed all provided datasets from Jonathan, focusing on claims, policies, and payments related to Sword AG.

- Data Cleaning & Transformation: Used Power Query to profile, clean, and merge datasets. Handled missing values, standardized formats (e.g., dates, monetary values), and ensured data quality for accurate analysis.

- Data Modeling: Established relationships between key tables (e.g., linking claims to policies and underwriters) to enable comprehensive analysis across dimensions.

- Calculated Metrics: Developed DAX measures to calculate KPIs such as Total Payment Amount, Average Payment per Claim, and Claim Count over time.

- Visualization & Dashboard Development: Built an interactive Power BI dashboard inspired by the provided model, incorporating slicers (for Year, Company, Segment, Underwriter), time-series charts, bar charts, and summary KPI cards.

- Analysis & Professional Scepticism: Critically analyzed the visualized data to identify trends, patterns, and potential red flags (e.g., unusually large claims, specific underwriter activity, payments in a particular period).

## Dashboard
<img width="760" height="433" alt="Insurance Claims" src="https://github.com/user-attachments/assets/a39ce17d-69db-42bf-8ae2-282ee80c6e3a" />

## Outcome
- The project delivered a centralized, interactive audit dashboard that provides management with immediate, data-driven insights. Key outcomes include:

- A clear visualization of the total financial exposure to Sword AG (€23.44M across 4923 claims).

- The ability to track the history and volume of claims and payments by year, company, city, and underwriter.

- Identification of key individuals (e.g., specific underwriters) and entities involved in the financial relationship.

- Data-supported points for discussing potential risks and anomalies during the management presentation.

## Recommendation
- Deep Dive on Anomalies: Investigate periods with significant spikes in claim volume or payment amounts for potential irregularities.

- Underwriter Review: Conduct a focused review of the underwriting process and authorizations for the underwriters with the highest financial exposure.

- Expand Data Scope: Request additional data (e.g., communication logs, contract details) to contextualize the findings and understand the nature of the claims.

- Continuous Monitoring: Implement this dashboard as a continuous monitoring tool to track ongoing transactions with Sword AG and other third parties in real-time.

## File
<a href="https://github.com/Luheto/Data-Analysis-Dashboard-Insurance-Claims/blob/main/ShieldGruppe_Dashboard_Solution.pbix">Insurance Claims Dashboard</a>
