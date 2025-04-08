# Supply-Chain-Performance-Analysis- Power BI

This project is a comprehensive Power BI dashboard built to analyze supplier performance, defect patterns, material-type issues, and plant-wise downtime.

🔍 **Objective**  
To transform raw operational data into meaningful insights, enabling data-driven decisions to reduce defects, improve vendor quality, and streamline supply chain processes.

## 📊 Key Features

- Total Defects & Downtime Analysis
- Top 5 Defective Vendors
- Sub-Category and Material-wise Defects
- Defect Trends Over Time
- Impact vs. No Impact vs. Rejected Defect Distribution
- Dynamic Filtering with Slicers (Vendor, Year, Plant, Defect Type)
- Defect Type & Material Distribution
- Forecasting with Time Intelligence
- Smart Alerts & Defect Ranking using DAX
- Defect Projection Visualization
- Defect Alert Card with Conditional Formatting

## 🧠 DAX Measures & Logic Highlights

- **YoY % Change** 
- **Dynamic Ranking** with `RANKX` for vendors & plant
- **TopN Filtering** with visuals for Top 5 Defective Vendors
- **Alert Logic** using `SWITCH()` + thresholds to highlight critical vendors
- **Projection Model** with `FORECAST.LINEAR()`

## 🏁 Outcomes

- Identified top defect contributors and their materials.
- Created smart forecasting to visualize future defect load.
- Enabled alerts for high-risk vendors to enable quick action.
- Presented a visually compelling narrative ready for stakeholders.



