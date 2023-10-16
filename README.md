# sql-challenge


The Data Analysis file contains a series of SQL queries that retrieve specific information from a database. The queries are designed to extract data related to employees and departments, such as employee details, hire dates, department managers, and frequency counts of employee last names. The data retrieved is not user-specific but rather depends on the contents of the database.

The data engineering file is primarily concerned with setting up a database schema. It first drops any existing tables to avoid conflicts. Then, it creates new tables for departments, employees, department employees, department managers, salaries, and titles. Each table is designed to hold specific types of data. Foreign keys are used to link these tables together based on relationships between the data they hold. Finally, it uses SELECT statements to retrieve data from each table, which helps verify that the tables have been set up correctly.

In summary, the Analysis is about querying an existing database to retrieve specific information, while the engineering is about setting up a new database schema and verifying its correctness.
