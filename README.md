# SQL Challenge

## Overview
This repository contains a data engineering project conducted at the fictional company Pewlett Hackard. The goal is to explore employee data from the 1980s and 1990s to perform data modeling, data engineering, and data analysis using SQL. The project includes the creation of a database schema, importing CSV data into SQL tables, and answering analytical queries.

---

## Features

### Data Engineering
- **Database Schema**: Create table schemas for six provided CSV files with:
  - Specified data types
  - Primary keys
  - Foreign keys
  - Other constraints as needed
- **Data Import**:
  - Import each CSV file into its corresponding SQL table.
  - Ensure table creation order respects foreign key dependencies.

### Data Analysis
- **Employee Queries**:
  - List the employee number, last name, first name, sex, and salary of all employees.
  - Identify employees hired in 1986 with their first name, last name, and hire date.
  - List department managers with department number, name, employee number, and personal details.
  - Show the department number, name, and details of each employee.
  - Filter employees named Hercules with last names starting with 'B', showing first name, last name, and sex.
- **Department Queries**:
  - List all employees in the Sales department with their details.
  - List employees in both Sales and Development departments, including department names.
- **Last Name Frequency**:
  - Display the frequency counts of all employee last names, sorted in descending order.

---

## Bonus Visualization
To assess data validity and present insights visually:
- Import the SQL database into Pandas for further analysis.
- Generate visualizations:
  - **Salary Histogram**: Show the most common salary ranges.
  - **Bar Chart**: Display average salary by job title.

---

## Repository Contents
- `schema.sql`: SQL scripts to create database schema.
- `data/`: Folder containing six CSV files with raw employee data.
- `analysis_queries.sql`: SQL queries for data analysis.
- `visualizations.ipynb`: Jupyter Notebook for bonus visualization tasks.
- `README.md`: Project documentation.

---

## How It Works
1. **Database Setup**:
   - Create a PostgreSQL database.
   - Run `schema.sql` to generate table schemas.
   - Import CSV files into respective tables using appropriate tools (e.g., `psql` or a database GUI).

2. **Data Analysis**:
   - Execute `analysis_queries.sql` to retrieve insights.
   - Review query results for patterns and trends.

3. **Bonus Visualization**:
   - Use SQLAlchemy to connect the database to a Jupyter Notebook.
   - Visualize key insights using matplotlib and Pandas.

---

## Getting Started
To replicate this project:
1. Clone this repository to your local machine.
2. Set up a PostgreSQL database.
3. Run the provided SQL scripts to create tables and import data.
4. Execute the analysis queries to extract insights.
5. Open `visualizations.ipynb` in Jupyter Notebook to generate visualizations.

---

## Notes
- Ensure all API keys or sensitive credentials are excluded from the repository (e.g., use `.gitignore`).
- Modify query parameters to suit specific analysis needs.
- Test all database connections before running scripts.

---

## Acknowledgments
This project was designed to develop data engineering and SQL skills, including database design, ETL processes, and data analysis.
