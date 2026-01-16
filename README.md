# Exploratory Data Analysis (EDA) Using SQL

## 📊 Project Overview
This project demonstrates comprehensive Exploratory Data Analysis on a sales dataset using SQL. The analysis explores sales trends, customer behavior, and product performance to derive actionable business insights through data-driven queries and aggregations.

## 🛠️ Tools & Technologies
- **Database Management System:** Microsoft SQL Server
- **Development Environment:** SQL Server Management Studio (SSMS)
- **Query Language:** SQL (T-SQL)
- **Version Control:** Git & GitHub
- **Data Format:** CSV files and SQL database backup

## 📁 How to Access the Files

### Repository Structure
```
├── scripts/           # SQL query files for analysis
├── datasets/          # Raw data files
│   ├── csv-files/     # CSV source files (Bronze, Silver, Gold layers)
│   └── DataWarehouseAnalytics.bak  # SQL Server database backup
└── README.md          # Project documentation
```

### Setup Instructions
1. **Clone the repository:**
```bash
   git clone https://github.com/Subash-Nagaraj-V/Exporatory-Data-Anlaysis-EDA-Using-SQL.git
```

2. **Restore the database:**
   - Open SQL Server Management Studio (SSMS)
   - Right-click on "Databases" → Select "Restore Database"
   - Choose the `DataWarehouseAnalytics.bak` file from the datasets folder
   - Complete the restoration process

3. **Execute SQL scripts:**
   - Navigate to the `scripts/` folder
   - Open the SQL files in SSMS
   - Run the queries against the restored database

4. **Alternative - Load CSV files:**
   - Import CSV files from `datasets/csv-files/` into your SQL Server
   - Use the Import/Export Wizard in SSMS

## 📊 Database Schema
The project uses a **data warehouse design** optimized for analytics:

**Main Sales Table (Fact Table):**
- `gold.fact_sales` - Stores sales transactions with amounts, quantities, and dates

**Supporting Tables (Dimension Tables):**
- `gold.dim_customers` - Customer information
- `gold.dim_products` - Product details

This structure allows for efficient analysis and reporting on sales data.

## 🔍 Key SQL Concepts Used
- **Aggregate Functions:** SUM(), COUNT(), AVG(), MIN(), MAX()
- **Date Functions:** FORMAT(), DATEDIFF(), YEAR(), MONTH()
- **Grouping & Filtering:** GROUP BY, HAVING, WHERE clauses
- **Set Operations:** UNION, UNION ALL
- **Data Type Handling:** DISTINCT, NULL handling
- **Subqueries and CTEs:** For complex data transformations

## 💡 Key Learnings
- Practical application of SQL for business analytics
- Data warehouse concepts and star schema implementation
- Writing optimized queries for large datasets
- Translating business questions into SQL queries
- Time-series analysis and trend identification
- Data aggregation techniques for reporting
- Best practices for database structure and organization

## 📧 Contact
**Subash Nagaraj V**
- **Email:** subashnagaraj796@gmail.com
- **LinkedIn:** [linkedin.com/in/subashnagaraj](https://www.linkedin.com/in/subashnagaraj)
- **GitHub:** [github.com/Subash-Nagaraj-V](https://github.com/Subash-Nagaraj-V)

## 📄 License
This project is open source and available under the MIT License. Feel free to use this project for learning and educational purposes.

---

⭐ **If you find this project useful, please consider giving it a star!**

💬 **Feedback and contributions are welcome!**
