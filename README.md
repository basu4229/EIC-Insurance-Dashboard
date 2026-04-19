# EIC-Insurance-Dashboard
This Power BI dashboard provides a comprehensive analysis of insurance policy performance, premium collection, and claims distribution from 2014 to 2018. It is designed to identify high-value segments, claim trends, and overall profitability.

Key Performance Indicators (KPIs):
Policies Opened: 57K total policies issued.
Total Premium: $383.9M in revenue generated.
Total Claims Paid: $333.7M disbursed to policyholders.
Premium to Claims Ratio: 113.8%, indicating that total premiums slightly exceed claims.
Average Premium: $7K per policy.
Average Claim: $6K per claim.

Visual Analysis Breakdown
1. Customer Segmentation: "Who buys our policies?"
A horizontal bar chart categorizing policyholders by vehicle type.
Top Segments: Motor cycles (16.2k) and Trucks (10.3k) represent the largest volume of policies.
Niche Segments: Special construction and Station Wagons represent the lowest policy counts.
2. Claims Trend: "Who claims the most?"
A ribbon chart showing the volume of claims across different vehicle categories from 2014 to 2018.
Observation: There is a visible shift in claim rankings over the years, with specific categories like "Automobile" and "Truck" consistently contributing to high claim volumes.
3. Demographics: "Sex 0 makes more claims"
A donut chart analyzing claims by gender (represented here as binary categories).
The data indicates a significant skew, with one demographic (labeled "0") accounting for the majority of claims (approx. 70.46%).
4. Profitability Heatmap: "Profitable Segments"
A detailed grid cross-referencing vehicle usage (e.g., Agriculture, Ambulance, Car Hire) against the policy years (2014–2018).
Insight: Highlights areas of high profitability (green) versus high loss/risk areas (red). For example, "Agriculture" shows high percentage growth/profitability in recent years.
5. Correlation: "Premium vs. Claim (averages)"
A scatter plot comparing Average Premium against Average Claim.
Most data points are clustered in the lower-left quadrant ($0 - $100k), suggesting that the majority of policies and claims are for standard, lower-value amounts, with a few high-value outliers.
Technical Summary
🛠 Tools & Technologies Used:
Power BI Desktop – Data visualization and dashboard creation
Power Query – Data cleaning and transformation (ETL process)
DAX (Data Analysis Expressions) – KPI calculations and measures
Excel / CSV Dataset – Data source handling
Data Modeling – Relationship building and schema design
Data Scope: 5-year historical insurance data (2014-2018).
Objective: To enable data-driven decisions regarding policy pricing, risk assessment, and market focus.

Business Problem
Insurance companies often struggle to balance premium pricing and claim payouts, leading to reduced profitability. There is limited visibility into:
:Which customer segments generate the most revenue vs. highest claims
:How claim patterns change over time
:Which policies or vehicle categories are high-risk or highly profitable
:Whether premium collection is sufficient to cover claim liabilities
 Without clear insights, it becomes difficult to make informed decisions on pricing, underwriting, and customer targeting

Key Impact:
Improved Profitability Analysis
Identified that the premium-to-claims ratio (113.8%) is only marginally profitable, highlighting the need for pricing optimization.
Better Risk Identification
Pinpointed high-claim segments (e.g., Trucks, Automobiles), enabling more accurate risk assessment and underwriting strategies.
Targeted Customer Strategy
Revealed top policy segments (Motor Cycles, Trucks), helping businesses focus on high-volume and high-value customers.
Data-Driven Pricing Decisions
Enabled comparison of average premium vs. claims to refine pricing models and reduce loss-making policies.
Enhanced Decision-Making
Provided a centralized, interactive dashboard for stakeholders to quickly monitor trends and take action.  
Data Source Details:
Original Source: According to the text, the dataset originates from mandel.com.
Content: It contains approximately 11 megabytes of vehicle insurance data, which is commonly used for machine learning projects, such as predicting claim probabilities or identifying fraudulent activities.
Association: The text explicitly links this data to the Ethiopian Insurance Corporation.
Screenshot/ Demo:
Show what the Dashboard Looklike :.<img width="1909" height="993" alt="EIC Insurance   Claims Dashboard - Screenshot" src="https://github.com/user-attachments/assets/164878de-eaac-4083-86fa-d2ad4a482cd9" />
