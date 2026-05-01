# 🎬 Movie Industry Analysis – SQL

## 📌 Project Overview
This project analyzes movie industry data using SQL to uncover trends related to actors, directors, and movie production.

---

## 🛠 Tools Used
- SQL (MySQL / PostgreSQL)

---

## 📊 Key Analysis Performed
- Identified top actors based on number of movies
- Analyzed director contributions
- Found most frequently produced movies
- Explored relationships using JOIN operations

---

## 🧠 Example Queries

### Top Actor by Movie Count
```sql
SELECT name, COUNT(*) AS total_movies
FROM crew
GROUP BY name
ORDER BY total_movies DESC
LIMIT 1;