# 🗄️ SQL Workbench Roadmap (Oracle SQL & MySQL)

This document outlines the step-by-step roadmap for mastering relational databases using **Oracle SQL** and **MySQL**.

---

## 🛣️ High-Level Overview

```
Phase 1: Environment Setup & Fundamentals
   └── RDBMS Architecture, ER Modeling, Oracle/MySQL Client Configuration
Phase 2: Data Definition (DDL) & Data Manipulation (DML)
   └── Table Schemas, Data Types, Constraints, Data Modifications
Phase 3: Data Retrieval & Analytics (DQL)
   └── Filtering, Aggregations, Grouping, MySQL vs. Oracle Built-in Functions
Phase 4: Advanced Querying & Multi-Table Operations
   └── Joins, Correlated Subqueries, CTEs, Set Operations
Phase 5: Performance Tuning, Objects & Procedural SQL
   └── Indexes, Views, Transactions (TCL), PL/SQL & MySQL Stored Routines
```

---

## 📅 Execution Plan & Checklist

### 🔹 Phase 1: Environment Setup & Fundamentals
- [ ] Understand core RDBMS architecture and normalization (1NF, 2NF, 3NF, BCNF).
- [ ] Install & configure database tools:
  - **Oracle SQL:** Oracle Database XE, SQL*Plus, Oracle SQL Developer.
  - **MySQL:** MySQL Server, MySQL Workbench, MySQL Shell.
- [ ] Master platform-specific data types (`VARCHAR2` vs `VARCHAR`, `NUMBER` vs `DECIMAL`/`INT`, `DATE` / `TIMESTAMP`).

### 🔹 Phase 2: Core Data Definition (DDL) & Data Manipulation (DML)
- [ ] **DDL Execution:** Practice `CREATE TABLE`, `ALTER TABLE`, `TRUNCATE TABLE`, `DROP TABLE`, and `RENAME`.
- [ ] **Integrity Constraints:** Implement `PRIMARY KEY`, `FOREIGN KEY`, `NOT NULL`, `UNIQUE`, `CHECK`, and `DEFAULT`.
- [ ] **DML Operations:** Execute `INSERT INTO`, `UPDATE`, and `DELETE` queries safely.

### 🔹 Phase 3: Data Retrieval & Analytics (DQL)
- [ ] Basic Filtering: `SELECT`, `WHERE`, `DISTINCT`, `ORDER BY`.
- [ ] Pattern Matching & Range Queries: `LIKE`, `IN`, `BETWEEN`, `IS NULL`.
- [ ] Dual Table & Scalar Functions: Oracle `DUAL` table vs. MySQL literals.
- [ ] Aggregations: `COUNT()`, `SUM()`, `AVG()`, `MIN()`, `MAX()`.
- [ ] Grouping: Master `GROUP BY` and condition filtering using `HAVING`.

### 🔹 Phase 4: Advanced Querying & Multi-Table Operations
- [ ] **Joins:** Master `INNER JOIN`, `LEFT OUTER JOIN`, `RIGHT OUTER JOIN`, `FULL OUTER JOIN` (Oracle native / MySQL workaround), `SELF JOIN`, and `CROSS JOIN`.
- [ ] **Subqueries:** Scalar, multi-row (`IN`, `ANY`, `ALL`), correlated subqueries, and conditional existence (`EXISTS` / `NOT EXISTS`).
- [ ] **CTEs:** Common Table Expressions using `WITH` clause for readable recursive & non-recursive queries.
- [ ] **Set Operators:** Compare and contrast `UNION`, `UNION ALL`, `INTERSECT`, and `MINUS` (Oracle) / `EXCEPT` (MySQL 8.0+).

### 🔹 Phase 5: Database Objects, Transactions & Procedural SQL
- [ ] **Views:** Standard Views, Read-Only Views, and Materialized Views (Oracle).
- [ ] **Indexes & Optimization:** Create B-Tree and Unique indexes; evaluate query efficiency using `EXPLAIN PLAN` (Oracle) / `EXPLAIN` (MySQL).
- [ ] **Transaction Control (TCL):** Understand ACID properties, `COMMIT`, `ROLLBACK`, `SAVEPOINT`, and isolation levels.
- [ ] **Procedural Extensions:**
  - **Oracle PL/SQL:** Anonymous blocks, Cursors, Exception handling, and Triggers.
  - **MySQL:** Stored Procedures, User-Defined Functions (UDFs), and Triggers.

---

## 📊 Milestone Tracker

| Phase | Description | Status | Target Date |
| :--- | :--- | :---: | :---: |
| **Phase 1** | Fundamentals & Tool Setup | ⏳ In Progress | — |
| **Phase 2** | DDL & DML Commands | 🟩 Pending | — |
| **Phase 3** | Data Retrieval (DQL) & Aggregations | 🟩 Pending | — |
| **Phase 4** | Joins, Subqueries & CTEs | 🟩 Pending | — |
| **Phase 5** | Database Objects & Procedural SQL | 🟩 Pending | — |