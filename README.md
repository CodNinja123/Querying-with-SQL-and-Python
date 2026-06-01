# Querying with SQL & Python (Chinook Digital Music Store Analysis)

## 📌 Project Overview
This data analytics project leverages Python, SQLite, and Pandas to interrogate the relational database structure of the fictional **Chinook Digital Music Store**. The objective is to unpack complex business entities, execute database joins, analyze sales volumes, and compile structural reporting matrices directly from an internal `sqlite3` data connection.

## 🛠️ Technology Stack
* **Environment:** Anaconda Navigator / Jupyter Notebook (Python 3)
* **Core Engine:** SQLite (`sqlite3`)
* **Data Processing:** Pandas
* **Data Visualization:** Matplotlib

## 🔍 Core Analytical Discoveries
The operational workflow answered three key operational queries using targeted SQL operations:
1. **Top 10 Best-Selling Tracks:** Extracted and ordered via aggregated track IDs and transactional purchase lines.
2. **Global Revenue Contributions:** Categorized and aggregated financial metrics across global billing destinations.
3. **Top Performing Sales Representative:** Multi-table customer and employee relational metrics aggregated by gross total transactional volume.

*Note: DataFrames are outputted using clean, human-readable 1-based indexing.*

## 💾 Project Artifacts Produced
* `Untitled.ipynb`: The complete execution notebook containing database queries and code logic.
* `Chinook_Top_Country_Revenue_Summary.csv`: Aggregated global sales distribution dataset.
