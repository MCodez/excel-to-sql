# excel-to-sql
## This repository will provide you Python3 code to convert any Workbook to a SQL Database.

This Python3 code can convert Workbook (.xlsx) {with many sheets} to a SQL Database (.sqlite) {with corresponding tables}. 

## Packages Required :
1. OPENPYXL {can be installed by pip : pip install openpyxl}
2. SQLITE3  {can be installed by pip : pip install sqlite3}
3. PYTHON 3.6 {python.org}

## Command :
```console
py@bar : python exceltosql.py <workbookname> <sqldatabasename>
```

## Working :
1. Each table will be created for each Sheet in workbook.
2. First row of sheet will be used for columns names for SQL Table.
3. Extra rows in EXCEL sheet will be termed as None and will be added to DB. It will not affect the data in the database and one can delete empty rows from Sheet before running code.


