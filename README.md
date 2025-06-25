# SQL-Task2
# Data Insertion and Null Handling in SQL
## Objective
Practice basic SQL operations (INSERT, UPDATE, DELETE) while handling null values and default constraints.
## Database Schema
table:Employees
Columns:
  - EmpID (PRIMARY KEY)
  - Name (TEXT NOT NULL)
  - Department (TEXT, allows NULL)
  - Salary (REAL, DEFAULT 25000)
## Tools Used
- SQLiteStudio for SQL execution
## SQL Operations Performed
### 1. Table Creation
- Created Employees table with appropriate constraints
- Set default salary value and null handling
### 2. Data Insertion
- Inserted 4 employee records
- Demonstrated NULL value insertion
- Used default value for salary column
### 3. Data Updates
- Updated NULL departments to 'Admin'
- Increased IT department salaries by $5000
### 4. Data Deletion
- Removed employees with salary less than $30000
- Final result: 2 remaining employees
## Key Learning Points
1. NULL Handling: Proper use of IS NULL in WHERE clauses
2. Default Values: Automatic application when columns omitted
3. Conditional Updates:Using WHERE clauses for targeted updates
4. Data Integrity:Understanding impact of DELETE operations
## Author
ABISHREE S
