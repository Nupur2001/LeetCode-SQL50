# 🔠 Types of SQL Commands

SQL commands are categorized into five main types based on their functionality:

---

## 📥 1. DML – Data Manipulation Language

Used to manipulate data within existing tables.

| Command  | Description                              |
|----------|------------------------------------------|
| `SELECT` | Retrieves data from a table               |
| `INSERT` | Adds new data into a table                |
| `UPDATE` | Modifies existing data                    |
| `DELETE` | Removes data from a table                 |

---

## 🛠️ 2. DDL – Data Definition Language

Used to define and manage database structures.

| Command    | Description                                 |
|------------|---------------------------------------------|
| `CREATE`   | Creates tables, views, indexes, etc.        |
| `ALTER`    | Modifies an existing table structure        |
| `DROP`     | Deletes objects like tables or views        |
| `TRUNCATE` | Removes all records from a table (faster)   |
| `RENAME`   | Renames a database object                   |

---

## 🔒 3. DCL – Data Control Language

Used to control access to data in the database.

| Command   | Description                          |
|-----------|--------------------------------------|
| `GRANT`   | Gives privileges to users            |
| `REVOKE`  | Removes privileges from users        |

---

## 🔄 4. TCL – Transaction Control Language

Used to manage transactions in a database.

| Command     | Description                                   |
|-------------|-----------------------------------------------|
| `COMMIT`    | Saves all changes made by the transaction     |
| `ROLLBACK`  | Undoes changes since the last COMMIT          |
| `SAVEPOINT` | Sets a savepoint within a transaction         |
| `SET TRANSACTION` | Defines characteristics of a transaction |

---

## ⚙️ 5. DQL – Data Query Language

Primarily focused on querying data.

| Command  | Description                     |
|----------|---------------------------------|
| `SELECT` | Used to retrieve data from tables |

> 🔁 Note: `SELECT` is sometimes categorized under **DQL**, but it's also considered a part of **DML** by some systems.

---

Would you like me to append this to your `.md` file or create a new one with this content?
