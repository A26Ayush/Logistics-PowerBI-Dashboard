**1. Overview of the Dashboard**

You have created an interactive business intelligence dashboard to monitor key performance metrics (KPIs) and operational insights for a logistics or transportation company. The dashboard allows users to explore data dynamically, answering key business questions like revenue trends, fleet utilization, driver performance, and customer insights.


**2. Data Sources and Structure**

The second image shows your data tables and their relationships. These are the main tables you used:

Customers – Customer details including type, contract info, and potential revenue.

Drivers & Driver Monthly Metrics – Driver information and monthly performance stats (miles, hours, on-time delivery, fuel efficiency).

Trips & Loads – Trip-specific data including distances, hours, fuel consumption, and linked customer loads.

Trucks & Trailers – Fleet assets with details like make, model, acquisition date, and capacity.

Facilities – Terminal and facility locations.

Routes – Route details including origin/destination, mileage, and rates.

Fuel Purchases & Maintenance Records – Costs, gallons, and maintenance logs for fleet management.

Safety Incidents & Delivery Events – Incident tracking, claims, and delivery-related events.

Truck Utilization Metrics – Summary metrics for truck usage including total revenue, miles, and trips completed.

These tables are linked using primary and foreign keys in a relational model, allowing you to combine operational, financial, and performance data efficiently.


**3. Data Preparation**

You used Power Query in Power BI to clean and prepare the data. The steps likely included:

Importing Data – Loaded Excel, CSV, or other data sources into Power BI.

Cleaning Columns – Removed unnecessary columns, handled missing values, and standardized column names.

Merging Tables – Linked related tables using keys (e.g., customer_id, driver_id, load_id) to create relationships.

Calculations & Measures – Added calculated columns like Total Revenue, Miles per Trip, Fuel Cost per Mile, etc.

Filtering & Transformation – Applied filters for active drivers, trips within certain dates, and other operational constraints.

This preparation ensures that your dashboard is accurate, interactive, and responsive to business questions.


**4. Key Interactive Charts**

The first image shows the four main chart areas:

KPI Overview – Top-level metrics like Total Revenue, Fuel Cost, Total Trips, Maintenance Cost, Active Trucks, and Incidents.

Revenue and Costs Analysis

Revenue by Customer & Route – Shows which customers or routes generate the most revenue.

Cheapest Fuel Cost by City – Highlights fuel efficiency opportunities.

Fleet Utilization & Trips

Bar charts of revenue by fleet or driver.

Scatter plot showing the relationship between total miles and revenue.

Maps showing home terminals and trip coverage.

Driver Performance & Customer Insights

Driver-wise on-time delivery rates and miles covered.

Customer-wise revenue, pieces ordered, and relationships between loads and revenue.

Maps showing incident locations for operational risk monitoring.


**5. Business Insights Enabled**

This interactive dashboard allows you to answer business questions such as:

Which customers and routes generate the highest revenue?

Which drivers and trucks are most efficient and reliable?

Where are operational risks or safety incidents concentrated geographically?

How does fuel cost vary across cities and routes?

How is total revenue correlated with miles covered, loads, and fleet utilization?

Which customers are top performers and contribute most to revenue?
