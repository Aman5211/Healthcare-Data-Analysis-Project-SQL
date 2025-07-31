# Healthcare-Data-Analysis-Project-SQL
This project is a hands-on SQL portfolio exercise built over a 30-day learning period. It focuses on real-world queries using a hospital database to derive meaningful insights from healthcare data. The goal is to practice and demonstrate SQL skills such as data aggregation, filtering, ordering, grouping, and analytical functions.

🏥 Project Dataset
The dataset simulates a hospital management system and contains fields like:

hospital_name

department

patients_count

doctors_count

medical_expenses

admission_date

discharge_date

location

📌 Objectives & SQL Queries
Below are the 10 key problems tackled in this project:

Total Number of Patients
→ Sum of all patients treated across all hospitals.

Average Number of Doctors per Hospital
→ Calculated using AVG() grouped by hospital name.

Top 3 Departments with the Highest Number of Patients
→ Ordered in descending order to identify the busiest departments.

Hospital with the Maximum Medical Expenses
→ Identified using ORDER BY and LIMIT.

Daily Average Medical Expenses
→ Expense divided by length of stay per patient.

Longest Hospital Stay
→ Difference between discharge and admission date.

Total Patients Treated Per City
→ Aggregated patient count grouped by location.

Average Length of Stay Per Department
→ Helps identify departments where patients stay longer.

Department with the Lowest Number of Patients
→ Can be useful for resource allocation.

Monthly Medical Expenses Report
→ Summarized using EXTRACT(Month) to show trends over time.

🛠️ Tools & Technologies
SQL (Structured Query Language)

PostgreSQL / MySQL / SQLite (any compatible RDBMS)

Any SQL execution environment (e.g., MySQL Workbench, pgAdmin, DB Fiddle)

🚀 How to Use
Clone the repository.

Import the sample dataset (you can mock it using the schema).

Run each SQL query in the respective SQL environment.

Analyze and visualize results as needed.

📚 Learning Outcome
This project helps develop a foundational understanding of how to:

Write efficient SQL queries.

Perform data analysis with SQL.

Interpret healthcare data in a structured format.

Use SQL functions for business reporting.
