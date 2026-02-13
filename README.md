# customer_behavior_analysis
End-to-end Customer Shopping Behavior Analysis using python(Pandas), SQL(PostgreSQL), and Power BI to drive all retail growth and subscription conversion 

Customer Shopping Behavior Analysis: End-to-End DA Project

Overview
This project provides a data-driven deep dive into retail consumer patterns using a dataset of 3,900 transactions. By integrating Python for data integrity, PostgreSQL for advanced querying, and Power BI for visualization, the project identifies key revenue drivers and untapped subscription opportunities.


 Dataset
•	Source: Customer Shopping Behavior Dataset.
•	Size: 3,900 rows and 18 features.
•	Key Variables: Customer demographics (Age, Gender), Purchase details (Category, Amount, Season), and Behavioral metrics (Subscription status, Review ratings).


Tools & Technologies
•	Data Cleaning/EDA: Python (Pandas, NumPy, Matplotlib).
•	Database: PostgreSQL (Structured querying and segmentation).
•	Visualization: Power BI (Interactive Dashboard).
•	Reporting: Microsoft Word (PDF Analysis Report).
•	Presentation: Gamma AI (AI-powered professional slide deck).


Project Steps
1.	Data Cleaning (Python): Handled 37 missing values in "Review Rating" via median imputation and standardized column names to snake_case.
2.	EDA: Explored distributions of spending across age groups and categories.
3.	Database Integration: Loaded cleaned data into PostgreSQL to perform complex joins and aggregations.
4.	SQL Analysis: Calculated KPIs such as revenue by gender ($157,890 for Males vs. $75,191 for Females) and identified 958 high-potential repeat buyers.
5.	Dashboarding: Built a Power BI dashboard to track average purchase amounts ($59.76) and review ratings (3.75).
6.	Reporting: Authored a professional PDF report and generated a presentation using Gamma to communicate strategic recommendations.


Dashboard Highlights
The Power BI dashboard features:
•	KPI Cards: Total customers, Average spend, and Average rating.
•	Demographic Breakdown: Revenue and sales volume by Age Group and Gender.
•	Subscription Analysis: A donut chart showing the 27% subscriber vs. 73% non-subscriber split.


Results & Recommendations
•	Top Segment: Identified Young Adults as the highest revenue contributors ($62,143).
•	Conversion Opportunity: Targeted 958 repeat buyers who are not yet subscribers to increase recurring revenue.
•	Product Strategy: Prioritized inventory for top-rated items like Gloves and Sandals.
•	Marketing: Recommended weekend-specific campaigns for the Clothing category to capitalize on high volume.


How to Run
1.	Python: Run Customer_Shopping_Behavior_Analysis.ipynb to clean the raw CSV.
2.	SQL: Import the cleaned CSV into PostgreSQL and execute customer_behavior_sql_queries.sql.
3.	Power BI: Open customer_behavior_dashboard.pbix to view interactive visuals (requires Power BI Desktop).
4.	Documentation: Review the Analysis_Report.pdf for deep-dive business insights.

Acknowledgments:
Special thanks to Amlan Mohanty for the excellent tutorial that guided this project's structure and analysis.
