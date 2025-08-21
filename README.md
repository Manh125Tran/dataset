This is a home repair service dataset. The dataset consists of 3 separate tables with different data volumes.
# Home Repair Service Dataset

The `home_repair_service_dataset.sql` file contains sample data for the home repair service.

Here are 2 ways to import this file into MySQL.

---

**## 1. Import into an existing database**
If you already have a database (e.g. `mydb`), run the following command in CMD/PowerShell:
```bash
mysql -u root -p mydb < "C:\Users\<username>\Desktop\home_repair_service_dataset.sql"
**## 2. Import into new database**
Create a new database before importing:
```bash
mysql -u root -p mydb < "C:\Users\<username>\Desktop\home_repair_service_dataset.sql"
Import data into the newly created database:
'''bash
mysql -u root -p home_repair_service < "C:\Users\<username>\Desktop\home_repair_service_dataset.sql"
