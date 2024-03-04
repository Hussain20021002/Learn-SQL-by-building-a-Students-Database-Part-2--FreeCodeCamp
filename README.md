# Learn-SQL-by-building-a-Students-Database-Part-2--FreeCodeCamp
This tutorial is a continuation of the Learn SQL by building a student database series from FreeCodeCamp. In this part, we'll continue working with PostgreSQL and SQL commands to query and manipulate our student database.

Instructions
---------------
->Start the Terminal: Begin by opening the terminal. Click the "hamburger" menu at the top left of the screen, go to the "Terminal" section, and click "New Terminal". Once opened, type echo hello SQL into the terminal and press enter.

->Rebuilding the Database: If your database is not available, you can use the .sql file created at the end of Part 1 to rebuild it. Split the terminal by clicking the "hamburger" menu at the top left, go to "Terminal", and click "Split Terminal". Then, enter psql -U postgres < students.sql to rebuild the database.

->Verify Database Structure: Log into the psql interactive terminal with psql --username=freecodecamp --dbname=postgres. Check if your database is present by listing the databases and connect to it.

->Explore Database Content: Display tables and relations, view details of the students table, ensure all data is present, and check details of other tables as needed.

->Create Script to Print Student Info: Create a script named student_info.sh to print information about computer science students from the database. Make it executable, add a shebang, and use echo to print headers and queries.

->Execute Script: Run the script to ensure it's working correctly.

->Query Database: Use SQL queries to retrieve specific information about students based on given criteria, such as GPA, major, or course enrollment.

->Final Steps: Add necessary commands to the script to fulfill all requirements mentioned in the tutorial, including printing average GPA, total number of students per major, list of unique courses, etc.

->Run Script: Execute the final script to see the results.

Additional Notes
--------------------
->Remember to use SQL functions like MIN, MAX, COUNT, AVG, etc., as needed to perform calculations and retrieve required data.

->Utilize SQL keywords such as JOIN, WHERE, GROUP BY, ORDER BY, and HAVING to filter and organize data effectively.

->Test each SQL query separately in the psql interactive terminal before incorporating it into the script to ensure accuracy.

Conclusion
------------
By following this tutorial, you'll gain hands-on experience with SQL queries and database management, further enhancing your skills in working with relational databases.
