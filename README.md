# Home Repair Service Dataset

The `home_repair_service_dataset.sql` file contains sample data for the home repair service. 
The dataset consists of 3 separate tables with different data volumes.
Here are 2 ways to import this file into MySQL.

---

## 1. Import into an existing database
If you already have a database (e.g. `mydb`), run the following command in CMD/PowerShell:

```bash
mysql -u root -p mydb < "C:\Users\<username>\Desktop\home_repair_service_dataset.sql"
```

Replace `<username>` with your Windows username.
Then enter your MySQL password to start the import.

---

## 2. Import into a new database
If you want to create a new database before importing:

```bash
mysql -u root -p -e "CREATE DATABASE home_repair_service;"
```

Then import the data into the newly created database:

```bash
mysql -u root -p home_repair_service < "C:\Users\<username>\Desktop\home_repair_service_dataset.sql"
```

---

## ⚠️ Note
- Replace `<username>` with your real Windows username (eg `C:\Users\Nguyen\...`).

- If you use **XAMPP/WAMP**, go to the `mysql/bin` folder in `xampp` or `wamp64` to run the commands.

- If the database already has data, import it into a new DB to avoid duplicate tables/keys errors.
