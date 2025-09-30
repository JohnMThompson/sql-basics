# SQL Basics Training – 1 Hour Intro

Welcome to the **SQL Basics Training Course**! 🎉  
This short, hands-on class will introduce you to fundamental SQL concepts using a lightweight SQLite database. By the end of this session, you’ll be able to query data with confidence and understand how SQL powers analytics and applications.

## 📘 Class Overview

In this course, you will learn and practice the following SQL keywords:

- `SELECT`
- `FROM`
- `WHERE`
- `ORDER BY`
- `JOIN`
- `GROUP BY`
- `LIMIT`
- Basic calculations inside `SELECT`

The lesson is interactive: you’ll write queries and see results immediately.

## 📂 Materials in this Repository

- **`sql_intro_class.sqlite`**

  SQLite database file with 10 customers, 8 products, and 100 sample orders.  
  Use this file during the exercises.

- **WORKSHEET.md**  
  Student-friendly worksheet (no answers) that you can follow directly on GitHub.

- **Slides / Notes (if provided)**  
  Additional class resources.

## 🛠️ Getting Set Up

We will use **DB Browser for SQLite**, a free and simple graphical tool for working with SQLite databases.

### 1. Install DB Browser for SQLite

- **Windows**: [Download installer](https://sqlitebrowser.org/dl/) and follow setup steps.
- **macOS**: [Download `.dmg`](https://sqlitebrowser.org/dl/) and drag to Applications.
- **Linux**: Install via your package manager. For example:

  ```bash
  sudo apt-get install sqlitebrowser   # Ubuntu/Debian
  sudo dnf install sqlitebrowser       # Fedora
  ```

### 2. Open the Training Database

1. Launch **DB Browser for SQLite**.
2. Go to **File → Open Database**.
3. Select `sql_intro_class_100_orders.sqlite` from this repo.
4. Click on the **Execute SQL** tab.
5. You’re ready to start running queries!

## ✅ First Query

Try this query to get started:

```sql
SELECT customer_name, country
FROM customers;
```

## 🙋 Need Help?

- Visit [DB Browser for SQLite documentation](https://sqlitebrowser.org/docs/) for setup and troubleshooting.
- Reach out to your instructor if you run into issues.

## ⚠️ Disclaimer

- All training materials and example data in this repository are for **educational purposes only**.
- Parts of this training, including documentation and training data, were generated using AI. All components have been reviewed and refined by the author.
