# SQL & Database Fundamentals (Day 1)

---

## 1. Core Concepts

* **SQL (Structured Query Language)**: The standard language used to talk to databases, fetch data, and manage tables.
* **DBMS (Database Management System)**: The overall concept/system for storing and managing digital data.
* **RDBMS (Relational Database Management System)**: A system based on a set of rules (introduced around 1970) to manage data stored in connected tables.
* **Database Software**: Real-world software tools built on RDBMS rules (e.g., MySQL, Oracle, PostgreSQL, DB2).

---

## 2. Table Structure

A **Table** is a collection of rows and columns. A single box/cell inside a table is called a **Value**.

| Database Term | Also Known As | What It Means |
| :--- | :--- | :--- |
| **Column** | Attribute / Field | Vertical category (e.g., `Name`, `Age`) |
| **Row** | Tuple / Record | Horizontal entry (e.g., one student's full info) |
| **Cell** | Value | The actual single piece of data (e.g., `John`) |

---

## 3. Key RDBMS Rules & Constraints

* **Primary Key**: A column with a **unique** value for every row (no duplicates, cannot be empty). Used to identify each record.
* **NOT NULL**: A rule that says a column **cannot be left empty**.
* **NULL**: Represents an **empty/missing** value.
* **Normalization (1NF to 5NF)**: Step-by-step rules to organize tables, remove duplicate data, and keep things clean.
* **Queries & Joins**: Rules that define how to write `SELECT` commands to retrieve and combine data from multiple tables.

---

## 4. Data vs Information

* **Data**: Raw, unorganized facts and figures without any context (e.g., `25`, `John`, `98.5`).
* **Information**: Processed, structured data that makes sense and has meaning (e.g., `John scored 98.5% in the exam`).

| Feature | Data | Information |
| :--- | :--- | :--- |
| **Meaning** | Raw facts with no meaning | Processed data with clear meaning |
| **Dependency** | Independent (Input) | Dependent on data (Output) |
| **Usage** | Cannot be used directly to make decisions | Used directly for decision-making |
| **Example** | `100`, `95`, `80` | `Average score = 91.6%` |

---

## 5. How Data Turns into Information

Data becomes useful information by processing it:
* **Summarizing**: Combining large amounts of data into a short overview.
* **Averaging / Calculating**: Doing math on numbers (e.g., calculating totals, averages, or percentages).
* **Filtering & Selecting**: Picking only the specific rows and columns you care about.
* **Visualizing**: Converting raw numbers into charts and graphs.
* **Adding Context**: Giving labels and meaning (e.g., labeling `25` as `Age = 25`).

---

## 6. Why Use SQL?

* **Easy to Learn**: Uses simple, English-like commands (e.g., `SELECT`, `WHERE`, `INSERT`, `DELETE`).
* **Handles Huge Data**: Easily filters and searches millions of rows in seconds.
* **Standard Language**: Works across almost all major database systems (MySQL, PostgreSQL, Oracle, SQL Server).
* **Data Integrity**: Enforces strict rules so you don't save duplicate or broken data.
* **Connects Tables (Joins)**: Allows you to combine related data across multiple tables smoothly.
