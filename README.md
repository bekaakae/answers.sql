
SQL Database Operations - README 
This guide explains how to create and drop databases using SQL queries stored in an answers.sql file using windows OS.

📋 Steps
1. Create answers.sql
Save the following queries in a file named answers.sql:

sql
-- Create a new database named 'salesDB'
CREATE DATABASE salesDB;

-- Drop (delete) the database named 'demo'
DROP DATABASE demo;
2. Save the File

Use Notepad and save as answers.sql (select "All Files" as type).

3. Run the SQL File
MySQL/MariaDB
sh
mysql -u [username] -p < answers.sql

4. Verify Operations
Check if salesDB was created and demo was dropped:
\l              -- PostgreSQL
⚠️ Troubleshooting
