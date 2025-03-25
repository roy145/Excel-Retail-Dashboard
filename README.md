📌 Overview
The Excel Retail Dashboard is a comprehensive, interactive reporting tool designed to provide key insights into sales, profitability, and return trends in a retail business. By leveraging Power Query for data transformation and advanced Excel features for visualization, this dashboard empowers users with a clear, data-driven decision-making framework.

The dashboard integrates three core datasets—Orders, People, and Returns—to deliver a holistic view of business performance. Users can explore key performance indicators (KPIs), analyze sales patterns, track return rates, and assess customer profitability, all through a dynamic and user-friendly interface.

🎯 Objectives
The primary goal of this dashboard is to streamline retail data analysis by transforming raw data into actionable insights. Key objectives include:

Enhancing business intelligence through data-driven KPIs.

Analyzing sales and profit trends across different regions, categories, and time periods.

Identifying high and low-performing product categories to optimize inventory and sales strategies.

Evaluating return rates to assess product performance and customer satisfaction.

Improving decision-making with a well-structured and interactive dashboard that allows filtering, slicing, and drill-down analysis.

📊 Data Processing & Methodology
The dashboard follows a structured data processing pipeline to ensure accuracy and efficiency:

1️⃣ Data Import & Preparation
Imported datasets (Orders, People, Returns) using Excel’s Get Data function.

Integrated Power Query Editor to clean, standardize, and transform raw data.

2️⃣ Data Cleaning & Transformation
Removed duplicate records and standardized column formats.

Handled missing values and ensured data integrity.

Created relationships between datasets for seamless data integration.

3️⃣ KPI Calculation & Data Modeling
Established key performance indicators (KPIs) such as:

Total Sales (Sum of Sales)

Total Profit (Sum of Profit)

Total Quantity Sold

Profit Margin

Total Number of Orders

Average Discount

Developed calculated fields to enable deeper analysis of sales, returns, and profitability.

### KPI Table Sample:\

![Screenshot 2025-03-25 145217](https://github.com/user-attachments/assets/466b02b5-cf62-4c07-a64c-6c039a33aba5)



4️⃣ Dashboard Creation & Visualization
Designed an interactive and visually appealing dashboard with clear insights.

Added a KPI summary table for at-a-glance performance tracking.

Implemented slicers and dynamic filtering for a more flexible user experience.

📌 Key Features & Analysis
✔️ KPI Overview
Total Sales, Total Profit, Total Quantity Sold, Number of Orders, Profit Margin, Average Discount

📈 Sales & Profitability Analysis
Overall sales trends

Regional and category-based profit distribution

Segment-wise revenue contribution

📊 Category Performance & Market Share
Category-wise profit analysis

Segment-wise sales percentage distribution

🌎 Geographical Insights
Sales distribution by country

Market-specific performance trends

🏆 Best & Worst Performing Products
Top 5 sub-categories based on sales and profit

Bottom 5 sub-categories with poor performance

🔄 Return Analysis & Customer Insights
Return rates by region and product category

Identification of high-value customers

Analysis of least profitable customers

📅 Yearly Sales Trends
Historical sales comparison to track growth patterns

Year-over-year profit margin analysis

🚀 Significance & Business Impact
The Excel Retail Dashboard plays a crucial role in improving business efficiency and profitability. Key benefits include:

✅ Data-Driven Decision Making – Empowers businesses with precise insights for strategy optimization.
✅ Enhanced Operational Efficiency – Reduces manual reporting efforts and provides automated, real-time insights.
✅ Improved Profitability Analysis – Helps businesses identify profitable products and underperforming areas.
✅ Customer Retention & Satisfaction – Enables targeted strategies based on return analysis and top customer profiling.
✅ Scalability & Adaptability – The dashboard can be adapted to other datasets and business models for broader applications.

### Data Sources
____________________________________________________________________________________________________________________________

The Dashboard is built using three data tables:
**1. Orders table:** Contains data on order details including customer info, products, sales, profit, and shipping details.
**2. People Table:** Lists sales representatives by region.
**3. Returns Table:** Contains return data, including which orders were returned across markets.

**Sample of Orders Data:**
Order ID	Order date	ship date 	Ship Mode	Customer ID	Customer Name	Segment	City	State	Country	Postal Code	Market	Region	Product ID	Category	Sub-Category	Product Name	Sales	Quantity	Discount	Profit	Shipping Cost	Order Priority
CA-2012-124891	7/31/2020	7/31/2020	Same Day	RH-19495	Rick Hansen	Consumer	New York City	New York	United States	10024	US	East	TEC-AC-10003033	Technology	Accessories	Plantronics CS510 - Over-the-Head monaural Wireless Headset System	2309.65	7	0	762.1845	933.57	Critical
IN-2013-77878	2/5/2021	2/7/2021	Second Class	JR-16210	Justin Ritter	Corporate	Wollongong	New South Wales	Australia		APAC	Oceania	FUR-CH-10003950	Furniture	Chairs	Novimex Executive Leather Armchair, Black	3709.395	9	0.1	-288.765	923.63	Critical
IN-2013-71249	10/17/2021	10/18/2021	First Class	CR-12730	Craig Reiter	Consumer	Brisbane	Queensland	Australia		APAC	Oceania	TEC-PH-10004664	Technology	Phones	Nokia Smart Phone, with Caller ID	5175.171	9	0.1	919.971	915.49	Medium
ES-2013-1579342	1/28/2021	1/30/2021	First Class	KM-16375	Katherine Murray	Home Office	Berlin	Berlin	Germany		EU	Central	TEC-PH-10004583	Technology	Phones	Motorola Smart Phone, Cordless	2892.51	5	0.1	-96.54	910.16	Medium
SG-2013-4320	11/5/2021	11/6/2021	Same Day	RH-9495	Rick Hansen	Consumer	Dakar	Dakar	Senegal		Africa	Africa	TEC-SHA-10000501	Technology	Copiers	Sharp Wireless Fax, High-Speed	2832.96	8	0	311.52	903.04	Critical
IN-2013-42360	6/28/2021	7/1/2021	Second Class	JM-15655	Jim Mitchum	Corporate	Sydney	New South Wales	Australia		APAC	Oceania	TEC-PH-10000030	Technology	Phones	Samsung Smart Phone, with Caller ID	2862.675	5	0.1	763.275	897.35	Critical
![image](https://github.com/user-attachments/assets/aa199870-b2ea-47af-9490-3613cad3f7e0)



🏁 Conclusion
The Excel Retail Dashboard is a powerful analytical tool that transforms raw sales data into meaningful business insights. By leveraging Power Query for data cleaning and Excel’s advanced visualization features, the dashboard ensures efficient monitoring of sales, profitability, and customer trends.

This project serves as a foundation for scalable retail analytics, enabling businesses to make data-driven decisions with confidence.

### Screenshot

![Screenshot 2025-03-25 144808](https://github.com/user-attachments/assets/c93f408c-e450-47e7-bd54-388759700310)
