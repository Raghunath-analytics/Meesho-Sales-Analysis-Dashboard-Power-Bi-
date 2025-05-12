# Meesho-Sales-Analysis-Dashboard (Power Bi)
 This Power BI dashboard analyzes Meesho's sales performance across all 28 Indian states using interactive visuals and custom DAX measures. The dashboard delivers clear insights into revenue trends, product size contributions, and regional performance.

 ## 📈 Objective
To build a dynamic, interactive sales dashboard for Meesho that helps in understanding geographical and categorical sales trends, optimizing inventory decisions, and identifying areas of improvement through data-driven insights.

## 📁 Dataset Used
- <a href="https://github.com/Raghunath-analytics/Meesho-Sales-Analysis-Dashboard-Power-Bi-/blob/main/Meesho%20Dataset.csv">Dataset</a>

## 📊 Business Questions Based on KPIs
- 💰 What is the total revenue distributed across different states and regions?
- 📦 Is the average revenue per order consistent across product sizes and categories?
- 📈 What factors are driving the total number of orders by region, size, or specific days?
- 🧾 How does the GST contribution vary by product category or order volume?
- 🚚 Are shipping charges impacting customer retention or final order value?
- 🧮 How does the Price (Excludes Tax) compare against total revenue, and what’s the profit margin after GST and shipping?
- 📊 Dashboard Interaction <a href="https://github.com/Raghunath-analytics/Meesho-Sales-Analysis-Dashboard-Power-Bi-/blob/main/Dashboard%20Screenshot.png">View Dashboard</a>

 ## 🛠 Tools & Techniques Used
- Power BI Desktop – Report development and visualization  
- DAX (Data Analysis Expressions) – Calculated columns and measures  
- Conditional Formatting – Enhanced visuals for top/bottom performance  
- Slicers – User-friendly interactive dashboard
- Removed Nulls & Duplicates-Ensured clean, consistent values in `State`, `Size`, `Order Status`, etc.
- Data Type Formatting - Converted date, revenue, and count fields into appropriate types.
- Created New Columns  - `Region`: Derived from `State` using DAX `SWITCH`. `Meesho Price`: Calculated as `Revenue - GST - Shipping`.

## ⚠️ Challenge Faced
-	Inconsistent State Names: Typos and casing differences required normalization before applying DAX logic.
-	Dynamic Filtering: Slicer sync across visuals (Region/Size) needed attention to ensure smooth user interaction.
-	Color Mapping in Map Visual: Power BI map visuals do not natively support dynamic color formatting based on text fields (like Region), so this was manually mapped.
-	Visual Overlap: Adjusted spacing and background colors for legibility in dark theme.

## ✅ Key Findings
-	Top State by Revenue: Uttar Pradesh (₹16.7K)
-	Highest Contributing Size: Free Size (54.32%)
-	Peak Sales Days: Monday and Tuesday
-	Most Common Order Status: Return to Origin (RTO)
-	Underperforming States: Arunachal Pradesh, Goa

## ✅ Final Conclusion
The Meesho Sales Analysis Dashboard successfully delivers actionable insights through a visually engaging and interactive Power BI interface. It provides a clear picture of sales performance across regions, product sizes, and order statuses. The North and South regions emerge as strong performers, while Free Size products dominate revenue contribution.

Despite challenges such as inconsistent data entries, regional mapping, and limited dynamic formatting in maps, these were effectively resolved through robust DAX logic, manual color encoding, and precise data cleaning. The dashboard empowers stakeholders to monitor KPIs, identify underperforming states, and align marketing and supply strategies more efficiently.

In essence, this project demonstrates the power of data storytelling using Power BI and DAX — laying a strong foundation for future enhancements like predictive analytics, demographic segmentation, and real-time data integration.







