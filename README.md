# Databases & SQL: SQL and Schema Design Notes

A comprehensive collection of notes, reference guides, SQL scripts, and schema design exercises covering core relational database concepts, data modeling, and performance optimization.

<img width="5568" height="3132" alt="image" src="https://github.com/user-attachments/assets/01842b57-7725-48c8-bd75-3034fd078efd" />


## 📌 Table of Contents
- [About the Repository](#about-the-repository)
- [Core Topics Covered](#core-topics-covered)
- [Repository Structure](#repository-structure)
- [Getting Started & Usage](#getting-started--usage)
- [Tools & Technologies](#tools--technologies)
- [Resources & References](#resources--references)

---

## 📖 About the Repository
This repository serves as a personal knowledge base and practical guide for mastering **Relational Databases**, structured querying, and data architecture. It bridges theoretical concepts (like normalization and ACID properties) with practical execution (writing efficient queries and designing scalable schemas).

## 🗂️ Core Topics Covered

### 1. Foundations & SQL Basics
- Relational Database Management Systems (RDBMS) fundamentals.
- **DDL (Data Definition Language):** `CREATE`, `ALTER`, `DROP`.
- **DML (Data Manipulation Language):** `SELECT`, `INSERT`, `UPDATE`, `DELETE`.
- **DCL & TCL:** Data control and transaction management (`COMMIT`, `ROLLBACK`).

### 2. Schema Design & Data Modeling
- **Entity-Relationship (ER) Diagrams:** Entities, attributes, and relationships (1:1, 1:M, M:N).
- **Normalization:** 1NF, 2NF, 3NF, and BCNF to minimize redundancy.
- **Denormalization:** When and why to break normalization rules for performance.
- Primary Keys, Foreign Keys, and Referential Integrity.

### 3. Advanced SQL & Query Optimization
- Complex **JOINS** (Inner, Left, Right, Full, Cross, Self).
- Subqueries, Correlated Subqueries, and Common Table Expressions (CTEs).
- Window Functions (`ROW_NUMBER()`, `RANK()`, `LEAD/LAG`).
- **Indexing:** B-Trees, Hash indexes, and strategies for query acceleration.
- Execution Plans and performance tuning.

### 4. Database Architecture & Internals
- **ACID Properties** (Atomicity, Consistency, Isolation, Durability).
- Transaction Isolation Levels and concurrency control (locking, MVCC).

---

## 📂 Repository Structure
```text
├── 01-foundations/          # Intro to RDBMS and basic SQL syntax
├── 02-schema-design/         # ER diagrams, normalization notes, and case studies
├── 03-advanced-sql/          # Window functions, CTEs, and complex optimization
├── 04-exercises/             # Practical SQL challenges and schema design problems
│   ├── leetcode-hackerank/   # Solutions to popular platform problems
│   └── mock-projects/        # E-commerce, social media, or banking schema setups
└── assets/                   # Images, diagrams, and cheat sheets
```

---

## 🚀 Getting Started & Usage
To run the SQL scripts and practice locally:
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   ```
2. **Setup your environment:** Choose a database engine (e.g., PostgreSQL, MySQL, SQLite).
3. **Execute scripts:** Navigate to the `04-exercises/` folder to run mock schemas and queries on your local instance.

## 🛠️ Tools & Technologies
- **Databases:** PostgreSQL / MySQL / SQLite *(Specify your preference)*
- **Design Tools:** Draw.io / dbdiagram.io / Lucidchart (for ER diagrams)
- **Formatting:** SQLFluff (or preferred SQL linter)

---

## 📚 Resources & References
- [PostgreSQL Documentation](https://postgresql.org)
- [Designing Data-Intensive Applications by Martin Kleppmann](https://dataintensive.net)
- Useful blogs, courses, or cheat sheets.
