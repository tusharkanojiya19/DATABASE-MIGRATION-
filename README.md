# DATABASE-MIGRATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: TUSHAR KANOJIYA

*INTERN ID*: CTIS7284

*DOMAIN*: SQL

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

*DESCRIPTION*: TASK-3: DATABASE MIGRATION

This task focuses on performing database migration between systems while ensuring data integrity and consistency. The objective of this task is to understand how data can be transferred from one database environment to another, such as from MySQL to PostgreSQL, without any loss or corruption. Database migration is an essential process in real-world applications when upgrading systems, changing database platforms, or improving performance and scalability.

In this task, a sample database named “company_db” is created to simulate a real-world environment. Initially, an attempt to use the database results in an error due to the database not existing. This highlights the importance of proper database creation before usage. The database is then successfully created and selected for further operations. This step ensures that the environment is correctly set up for data migration.

An “employees” table is created within the database with multiple attributes such as employee ID, name, email, salary, active status, and creation timestamp. The table structure is designed to store employee-related information in a structured format. Proper constraints such as PRIMARY KEY, NOT NULL, and UNIQUE are applied to maintain data integrity and avoid duplication of records.

After creating the table, data is inserted into the employees table. The records include employee names, email addresses, salaries, active status, and timestamps. The use of the NOW() function ensures that the current date and time are recorded for each entry. The insertion process is completed successfully, and the output confirms that multiple rows have been added without any duplicates or warnings.

During the process, minor warnings such as deprecated integer display width are observed, which indicate the importance of keeping database systems updated and following best practices. Additionally, the use of boolean values (TRUE/FALSE) for the active status demonstrates compatibility considerations when migrating data between different database systems, as some systems represent boolean values differently.

A verification step is performed using a SELECT COUNT(*) query to confirm the number of records in the table. The output shows that three records are successfully stored in the database. This step is crucial in database migration as it ensures that the data has been transferred correctly and completely.

The migration process involves not only transferring data but also ensuring that the structure, constraints, and relationships are preserved. Care is taken to maintain consistency in data types and formats so that the migrated database behaves correctly in the target system. This task demonstrates the importance of validating data after migration to ensure accuracy and reliability.

The deliverable of this task includes migration scripts and a summary of the process, showing how the database is created, structured, populated, and verified. Each step is carefully executed to ensure smooth data transfer and integrity.

Overall, this task provides practical experience in database migration and highlights the importance of planning, execution, and validation. It helps in developing a clear understanding of how data is managed across different database systems in real-world scenarios.

