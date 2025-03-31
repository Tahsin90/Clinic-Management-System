# Clinic-Management-System
1. Fragmentation
Fragmentation is the process of dividing a database into smaller pieces (fragments) to improve efficiency and performance in a distributed system.
Types of Fragmentation Used:

Horizontal Fragmentation: Dividing a table into subsets of rows based on certain conditions-Splitting the Doctor table based on the department (e.g., Cardiology, Neurology).
-Splitting the Patient table based on gender or age groups.

Vertical Fragmentation: Dividing a table into subsets of columns while maintaining the primary key for reconstruction-Storing contact details separately from other patient records to enhance security.
In this project, we've done fragmentation for doctor and patient table.
2. A function to calculate the total bill from the Bill table.
3.A function to get the last appointment date of a patient.
4.Stored procedures are precompiled SQL statements that execute a sequence of operations.(Procedure to add a new outpatient record,Procedure to update room status when a patient is discharged).
5.A semi-join is used in distributed databases to retrieve matching rows from one table based on another without returning duplicate data.
&.Performed Algerbric Relation to mactch various criterias-Retrieve patient names and their respective doctors,Retrieve only the names and phone numbers of doctors, Find all patients over 60 years old.
6.Canonical expressions optimize SQL queries by reducing redundancy and improving execution efficiency-Normalized complex queries to simpler ones.
7.Triggers automatically execute a defined action when a specific event occurs in the database-Trigger to automatically update room status when a patient is admitted,Trigger to log when a new appointment is made.

