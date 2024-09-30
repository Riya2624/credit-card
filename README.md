Credit Card Transaction Analysis

Overview: This project analyzes credit card transaction data, including revenue, transaction counts, and customer details. The process involves data preparation, SQL table creation, and data analysis in Power BI.

Steps: Prepare CSV: Gather data on revenue, transaction count, expenditure type, and customer info in CSV format.

Create SQL Tables: cusr_detail: Stores customer details. cc_detail: Contains transaction data. Import Data into SQL:

Use the COPY command to import CSV files into SQL. Clean and normalize the data for consistency.

Data Analysis: Analyze key metrics like transaction count, revenue by expenditure type, and customer demographics in Power BI using DAX queries.

Files: credit_card.csv: Raw data create_tables.sql: SQL table creation script credit_card_report.pbix: Power BI report Setup: Use PostgreSQL for database setup. Import CSV with SQL COPY command. Analyze the data in Power BI.
