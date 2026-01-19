# customer-shopping-behavior-analysis
Data analytics project showcasing customer behavior analysis using Python MySQL and PowerBI.
Customer Shopping Behavior Analysis
A Data Analytics Project using Python, SQL, and Power BI
Overview
This project analyzes customer shopping behavior using transactional retail data. The goal is to understand how customers interact with products, how much they spend, and what factors influence purchasing decisions. The project demonstrates an end-to-end data analytics workflow, from raw data to insights and visualization.
The analysis combines Python for data preparation, SQL for structured analysis, and Power BI for visualization, with findings summarized in a written report and presentation.
Dataset
•	Retail customer shopping behavior dataset
•	Records: ~3,900 transactions
•	Features include:
Customer demographics (age, gender, location)
Purchase details (item, category, amount, season)
Shopping behavior (discounts, subscription status, reviews)
Transaction attributes (shipping type, purchase frequency)
The dataset was originally provided in Excel format and processed using Python.
Tools & Technologies
•	Python (Pandas, NumPy) – data loading, cleaning, and exploratory analysis
•	Jupyter Notebook – development and analysis environment
•	SQL (PostgreSQL / MySQL / SQL Server) – data storage and querying
•	Power BI – interactive dashboard and data visualization
•	Gamma – presentation (PPT) creation
•	GitHub – version control and project documentation
Project Workflow
1.	Data Loading
Imported the dataset into Python using Pandas
2.	Exploratory Data Analysis (EDA)
Examined data structure and summary statistics
Identified missing values and inconsistencies
Explored distributions and key patterns
3.	Data Cleaning & Preparation
Handled missing values
Standardized column names
Created derived features such as age groups and customer segments
4.	Database Integration
Loaded the cleaned dataset into a relational database
Ran analytical SQL queries using PostgreSQL / MySQL / SQL Server
5.	SQL Analysis
Revenue analysis by category and demographics
Subscription vs non subscription behavior
Customer segmentation (new, returning, loyal)
Discount and shipping impact analysis
6.	Visualization
Built an interactive Power BI dashboard to present insights clearly
7.	Reporting & Presentation
Documented findings in a written report
Created a presentation deck using Gamma
Power BI Dashboard
The Power BI dashboard provides an interactive view of customer behavior and sales performance.
Key features include:
•	KPIs: total customers, average purchase amount, average review rating
•	Revenue and sales by product category
•	Revenue and sales by age group
•	Subscription status distribution
•	Interactive slicers for gender, category, subscription status, and shipping type
The dashboard allows stakeholders to explore trends and compare customer segments easily.
Key Results & Insights
•	A small percentage of customers (subscribers and loyal buyers) contribute a large share of revenue
•	Certain product categories consistently outperform others
•	Younger and middle-aged customers drive most sales
•	Subscription customers tend to have higher average spending
•	Discounts influence purchases but require careful optimization
How to Run This Project
1.	Clone the repository
2.	git clone https://github.com/your-username/customer-shopping-analysis.git
3.	Run the Python notebooks
Open Jupyter Notebook
Install required libraries:
pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
Execute the notebooks for EDA and data cleaning
4.	Set up the database
Create a database in PostgreSQL / MySQL / SQL Server
Load the cleaned dataset into the database
Run the provided SQL queries
5.	Open the Power BI dashboard
Connect Power BI to the database (or via Python)
Refresh data and explore visuals
Project Outcome
This project demonstrates practical data analytics skills, including data cleaning, SQL analysis, dashboard development, and business focused insight generation. It reflects a real world analytics workflow and is suitable for portfolio presentation or entry-level data analyst roles.
