# Logistics_shipping_analytics
Logistics Shipping Analytics Project
This project showcases my end-to-end data skills using a fully synthetic **5,000-row logistics shipping dataset** that I created, cleaned, and analyzed.  
The goal of this project is to demonstrate my ability to work with real-world-style operational data, build insights, and present them through SQL, analytics, and dashboard visualizations.

Project Purpose
I built this project to strengthen and demonstrate my skills in:
- Data modeling and dataset creation  
- Data cleaning and validation  
- SQL querying and analysis  
- Power BI dashboard development  
- Trend analysis and KPI reporting  
- Logistics and operations analytics  
- Portfolio-ready documentation and storytelling  

This project simulates a real logistics environment and allows me to analyze carrier performance, delivery times, shipping costs, and warehouse operations.

Dataset Overview
I created a 5,000-row dataset representing shipments from 2026–2029 across five major North American warehouses:
- Edmonton, AB  
- Calgary, AB  
- Vancouver, BC  
- Toronto, ON  
- Chicago, IL  

Each shipment includes:
- shipping_id  
- order_id  
- carrier  
- shipping_method  
- warehouse_location  
- ship_date  
- delivery_date  
- shipping_cost  
- delivery_status  

All data is fully synthetic and designed to mimic realistic logistics patterns.

What I Did in This Project
	1. Built the Dataset
	- Designed the schema  
	- Generated 5,000 rows of realistic shipping data  
	- Ensured sequential IDs, valid dates, and consistent logic  
	- Saved each table as CSV for easy import into tools  

	2. Cleaned & Validated the Data
	- Checked for duplicates  
	- Verified date logic (ship ? delivery)  
	- Standardized carrier and warehouse naming  
	- Ensured consistent cost and method patterns  

	3. Performed SQL Analysis
	I wrote SQL queries to explore:
	- Average delivery time by carrier  
	- Cost differences between shipping methods  
	- Warehouse performance metrics  
	- Seasonal delivery trends  
	- Carrier reliability scoring  
	- Delivery time distributions  

	4. Built a Power BI Dashboard
	My dashboard includes:
	- KPIs (avg delivery time, avg cost, total shipments)  
	- Carrier comparison visuals  
	- Delivery time trend lines  
	- Warehouse performance charts  
	- Cost breakdowns  
	- Filters for method, carrier, and location  

	5. Documented Insights
	I summarized key findings such as:
	- Which carriers deliver fastest  
	- Which shipping methods cost the most  
	- Which warehouses perform best  
	- Seasonal spikes in delivery times  
	- Cost vs. delivery-time tradeoffs  

	6. Packaged Everything for GitHub
	This repository includes:
	- `/data` — CSV files  
	- `/sql` — SQL queries  
	- `/dashboard` — Power BI file + screenshots  
	- `/docs` — project notes and visuals  
	- README.md — this document  

Key Insights (Examples)
- **Purolator Express** consistently has the fastest delivery times  
- **DHL Standard** tends to have the longest delivery windows  
- **Calgary and Edmonton** warehouses show the most consistent performance  
- **Shipping costs** are strongly tied to method (Express > Expedited > Standard)  
- **Seasonal slowdowns** appear in winter months  

Tools Used
- OpenOffice (CSV creation)  
- Power BI (visualization)  
- SQL (analysis)  
- Python (optional deeper analytics)  
- GitHub (version control & portfolio)  

Future Enhancements
- Add delays, lost shipments, or anomalies  
- Add customer and product tables  
- Build a machine learning model to predict delivery time  
- Add weather-based or seasonal effects  
- Expand to international shipments  

License
This dataset is fully synthetic and free to use for learning, portfolio building, and non-commercial projects.
