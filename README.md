📊 SQL Database Design & Analytical Reporting
This repository contains a complete relational database schema and a suite of complex SQL reports designed with SQLite. It demonstrates the ability to architect database structures, manage relational data, and perform advanced business intelligence queries.

🛠️ Project Structure
system_config.db: The live SQLite database file.

schema_definition.sql: Data Definition Language (DDL) scripts, including table creation with primary and foreign key constraints.

data_seeding.sql: Data Manipulation Language (DML) scripts for populating the database.

analytical_queries.sql: A collection of advanced SQL queries including:

Multi-level JOINs (connecting Users, Desktops, and Icons).

Aggregate Functions (COUNT, MAX).

Subqueries for precise data filtering.

Outer Joins for comprehensive reporting.

📈 Key Technical Highlights
Relational Integrity: Implementation of composite Primary Keys and cascading Foreign Keys.

Advanced Filtering: Queries designed to isolate specific user data and system configurations.

Reporting: Automated count of assets (Desktops) per user, handling null values and deleted records.

🚀 Usage
To explore the database, you can use any SQLite browser (e.g., DB Browser for SQLite) and run the scripts provided in the analytical_queries.sql file.
