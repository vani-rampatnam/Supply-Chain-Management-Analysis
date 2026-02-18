📊 Supply Chain Management Analytics Dashboard (Power BI)

🔎 Project Overview
This project is an end-to-end Supply Chain Analytics Dashboard built in Power BI, designed to analyze operational efficiency, supplier performance, inventory health, logistics optimization, and risk exposure.
The solution transforms raw supply chain data into a structured analytical model using data cleaning, feature engineering, DAX measures, and interactive visualizations to support business decision-making.
________________________________________

🏗 Architecture & Data Workflow
1️⃣ Data Sources
•	Structured supply chain dataset (CSV/Excel)
•	Supplier, Inventory, Logistics, and SKU-level transactional data

2️⃣ Data Processing
•	Excel for structured data extraction
•	Excel for initial validation
•	Power Query for preprocessing
•	Power BI Power Query for transformation & modeling

3️⃣ Data Modeling
•	Star schema modeling approach
•	Fact tables: Orders, Inventory, Manufacturing, Logistics
•	Dimension tables: Supplier, SKU, Product Category, Transport Mode
•	All in one Table Supply_Chain_Data.csv
________________________________________

🧹 Data Cleaning & Transformation

•	Validated and confirmed absence of missing values
•	Removed duplicate records
•	Standardized department-specific columns
(e.g., Lead_Time_Manufacturing, Lead_Time_Suppliers, Lead_Time_Orders)
•	Normalized categorical text fields
•	Corrected data types for accurate aggregations
•	Applied row-level filtering based on business rules
•	Rounded high-precision decimal values for reporting consistency
________________________________________
⚙️ Feature Engineering
Created derived analytical features to enhance business insights:
•	Risk_Factor (Defect / Delay / Cost-based classification)
•	Transport_Impact (High / Medium / Low)
•	Supplier_Quality scoring
•	Composite Risk_Score using weighted conditions
•	KPI measures using DAX:
o	Total Revenue
o	Avg Lead Time
o	Defect Rate %
o	Inventory Turnover
o	Understock / Excess Stock Count
o	Cost per Transportation
________________________________________

📊 Dashboard Modules

1️⃣ Executive Overview
•	Aggregated KPIs
•	Revenue distribution (Product & Transport Mode)
•	Geographic revenue visualization
•	Supply chain stage lead time comparison

2️⃣ Demand & Forecast Analysis
•	SKU-level stock vs demand comparison
•	Demand distribution by category
•	Top & bottom SKU performance
•	Average demand metrics
•	Inventory-demand gap identification

3️⃣ Inventory Optimization
•	Understocked, Excess, and Out-of-Stock SKUs
•	Inventory risk classification
•	Stock-out risk ranking
•	Product-wise inventory vs sales comparison

4️⃣ Supplier & Manufacturing Analysis
•	Manufacturing cost analysis
•	Production volume comparison
•	Lead time benchmarking
•	Supplier quality & defect rate evaluation
•	Risk-adjusted supplier performance scoring

5️⃣ Logistics & Transportation
•	Carrier performance quadrant (Cost vs Delivery Time)
•	Shipping cost distribution
•	Transportation mode contribution
•	Route frequency analysis
•	Cost efficiency evaluation

6️⃣ Risk & Sustainability Analysis
•	SKU-level risk categorization
•	Supplier risk contribution analysis
•	Lead time & defect impact assessment
•	Product-level risk distribution
•	High-risk SKU identification for prioritization
________________________________________
📈 Analytical Techniques Used
•	Descriptive statistics
•	KPI engineering
•	Risk scoring logic
•	Cross-filtering & drill-through implementation
•	Quadrant performance analysis
•	Percentage contribution analysis
•	Conditional formatting for risk identification
________________________________________
🛠 Technical Stack
•	Power BI (Data Modeling, DAX, Visualization)
•	DAX (Calculated columns & measures)
•	Power Query (M Language) for ETL
•	Excel for data extraction
•	Power Query for preprocessing
•	Excel for validation
________________________________________
📌 Limitations
The dataset does not contain a time dimension; therefore:
•	No time-series trend analysis
•	No seasonal forecasting
•	Analysis is cross-sectional (point-in-time)
________________________________________
🚀 Key Outcomes
•	Identified high-risk SKUs requiring replenishment
•	Detected supplier-specific quality risks
•	Highlighted cost concentration in specific carriers
•	Exposed supply-demand imbalance across product categories
•	Built a scalable analytical model for supply chain decision-making
________________________________________
🧠 Skills Demonstrated
•	Data Cleaning & Transformation
•	Dimensional Data Modeling
•	Advanced DAX Calculations
•	Business KPI Development
•	Risk Scoring & Classification
•	Supply Chain Analytics
•	Data Storytelling & Dashboard Design
________________________________________
👩‍💻 Author
Vani
Data Analyst Intern
Power BI | SQL | Python | Data Modeling | Business Intelligence
