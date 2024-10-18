**Create the sqlite databases from your .sql/csv/xlsx files.**
## 1. To prepare the SQL DB from a .sql file, Copy the file into data/sql directory and in the terminal, from the project folder, execute:

sudo apt install sqlite3

## Now create a database called sqldb:

sqlite3 data/sqldb.db
.read data/sql/<name of your sql database>.sql

## 2. To prepare a SQL DB from your CSV and XLSX files, copy your files in data/csv_xlsx and in the terminal, from the project folder, execute:

python src/prepare_csv_xlsx_sqlitedb.py