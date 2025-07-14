# CSV DATA TO SQL AUTOMATION
This project automates data cleaning, validation and loading `.csv`, to database SQL server using Python.
Industrial environmente where the data are generated automatically from testers.

# TECHNOLOGIES
- Python 3.13
- pandas
- pyodbc
- glob
- SQL Server

# OBJECTIVE
Automate repetitive data loading tasks, validating duplicates and applying minimal cleaning, to improve the efficiency  of the analysis process.

# CODE STRUCTURE
- Data cleaning with `pandas` (handling of `NaN`, rounding of decimals, creation of unique ID).
- Validation to avoid duplicates in the database.
- Secure insertion with error control in SQL table.

# HOW TO EXECUTE
1. Clone repository:
```bash
git clone 
```
2. Install dependences:
```bash
pip install -r requirements.txt
```
3. Configure database connection.
4. Notebook inicialization.

# SECURITY
This project doesn't  contain company data or real credentials.

# AUTOR
Developed by Jesús Sandoval, industrial processes.