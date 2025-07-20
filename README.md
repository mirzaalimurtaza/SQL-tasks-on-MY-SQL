# SQL-tasks-on-MY-SQL
# 📚 Library Management System with Tiered Membership – SQL Project

This SQL project models a *Library Management System* that supports *tiered user memberships* (STANDARD,ELITE), each with different borrowing rights and access levels.

The project demonstrates *relational database design, **normalization, and **analytical SQL queries* for tracking book loans, member activity, and overdue fines.

---

## 🧩 Key Features

- Tiered membership types with specific borrow limits
- Books borrowing and returning records
- Members’ account and activity tracking
- Late return fine calculation (optional)
- SQL queries for library usage analytics

---

## 🛠 Technologies Used

- *MySQL* 
- SQL (DDL, DML, DQL)
- DB schema design
- ER Diagram tools (draw.io)

---

## 🧱 Database Tables

| Table Name        | Description                             |
|-------------------|-----------------------------------------|
| Members         | Stores member details and tier info     |
| Membership_Tiers| Defines Bronze/Silver/Gold rules        |
| Books           | Contains book catalog data              |
| BORROWS         | Tracks borrow and return status         |
| Reading_history,recommendation |      |

---

## 🔍 Example Queries

- Show members who have borrowed more than 5 books in the past month
- List all overdue books by Gold members
- Count the number of books currently issued per tier
- Calculate total fines collected by membership tier

---

## This is the structure of my project 
## furthermore
---

## 🎯 Learning Outcomes

- Design normalized databases with real-world constraints
- Use foreign keys to model relationships
- Implement tiered access logic via SQL
- Write complex analytical queries using JOIN, GROUP BY, and subqueries

---

## 🚀 Future Enhancements

- Add stored procedures for issuing and returning books
- Build a web-based frontend (HTML + PHP/Python)
- Integrate with Python for visualization or reporting

---

## 📌 Note

This project is built as a *portfolio-level academic project* for practicing SQL skills and DBMS concepts. Contributions and feedback are welcome!
