# 🚖 Uber Trips Data Analysis – 2015 | Power BI Project
📌 Project Overview
This project analyzes Uber trip pickup records from January to December 2015 to understand demand trends, seasonal patterns, base-wise performance, and fleet deployment efficiency. The dataset contains dispatch base details, pickup timestamps, affiliated base numbers, and pickup locations.
Although fare, distance, and passenger details are not included, the dataset provides strong insights into trip volume behavior, time-based patterns, and operational performance.

📂 Dataset Summary


Total Records: 355


Total Columns: 4


Columns Included:


dispatching_base_number


pickup_datetime


affiliated_base_number


locationid




Time Range: 1 Jan 2015 – 31 Dec 2015


Key Information Type: Uber pickup trip events


Best Use Case: Trip trends, demand insights, and base-wise analysis



🛠️ Methodology
✅ 1️⃣ Data Cleaning


Checked dataset structure, dimensions, and column attributes


Identified and removed duplicate records


Handled missing values appropriately


Converted pickup_datetime into standardized datetime format


Corrected and validated data types to avoid analytical errors



🔄 2️⃣ Data Transformation
From the pickup datetime column, the following features were extracted:


Date


Day of the week


Hour of the day


Month


Additional transformations included:


Standardizing location IDs


Aggregating total trips by


day


hour


month


base number


location




These transformations converted raw data into structured, analysis-ready information.

📊 3️⃣ Data Visualization & Dashboard
Developed a Power BI Dashboard to bring insights to life.
⭐ Key KPI Cards
KPIInsightTotal Trips – 4MOverall Uber trips completed in the dataset periodMax Trips – 46KHighest trips recorded in a single periodAverage Trips – 11.67KAverage demand levelMax Active Vehicles – 4395Maximum vehicles deployedTotal Base Numbers – 6Total contributing operational bases

📈 Monthly Trip Trend (Line Chart)


January starts around 263K


Growth till March (492K)


Dip in April followed by rise


Peak in August (508K)


Decline from October onwards


Very low demand in Nov–Dec


📌 Insight: Strong seasonal demand — summer has highest rides, year-end lowest.

🏢 Trips by Base Number (Bar Chart)


B02664 – Highest (~2M)


B02617 – ~725K


B02682 – ~663K


B02598 – ~541K


B02675 – ~194K


B02512 – Lowest (~94K)


📌 Insight: B02664 is the backbone of Uber operations.

📅 Monthly Trip Summary Table
Helps identify:


Highest & lowest demand months


Base contributions each month


Overall performance


📌 Example:


Highest Month: July – 507,543 trips


Lowest Month: December – 57,646 trips



🚗 Active Vehicles by Base (Donut Chart)


B02664 – 46.95%


B02617 – 17.23%


B02682 – 15.43%


B02598 – 12.67%


B02675 – 4.88%


B02512 – 2.84%


📌 Insight: More vehicles = more trips = stronger operations.

📊 Monthly Active Vehicles (Bar Chart)


Jan: 32K → Feb: 45K → Apr: 56K


Stable between 47K–53K till September


Drop begins October → very low in Nov & Dec


📌 Insight: Vehicle deployment follows demand perfectly.

🎯 Interactive Filters


Month slicer for focused analysis


Dynamic visualization refresh



✅ Conclusion
Uber’s 2015 trip analysis highlights clear seasonal demand patterns, operational dominance of a few bases, and strong correlation between vehicle availability and ride demand.

🔍 Key Insights
✔ Peak Demand: June–August
✔ Lowest Demand: October–December
✔ Top Performing Base: B02664
✔ Efficient Fleet Strategy: Vehicles increase during high demand months
✔ Consistent Performers: B02617 & B02682
✔ Clear Demand–Fleet Relationship: More vehicles → More trips
✔ Predictable Customer Trend: Supports future forecasting

📊 Dashboard Preview
 <img width="1383" height="731" alt="Dashboard (3)" src="https://github.com/user-attachments/assets/e6614ea5-8e6c-4b17-9696-af3325526961" />


🔗 Project & Resources
📂 Dataset Link:https://drive.google.com/file/d/1uj0xGqt3t7w6AgoTNq8SksR2Ci3bbWJ1/view
