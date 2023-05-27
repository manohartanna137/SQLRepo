### Data base creation ###
- Writing a SQL statement to create a simple table Locations including columns                     country_id,country_name and region_id.        
- writing SQL statement to rename the table Locations to Locations_new. 
- Writing a SQL statement to add a column region_name to the table locations. 
- Writing a SQL statement to add a column ID to the table locations.  
- Writing a SQL statement to add a column state_province after region_id to the table locations. 

### Constraints ###
- Writing a SQL query to create the below table with (agent_name,agent_code,working_area).
- Writing a SQL query to create a table to achieve UNIQUE constraints for ord_num.
- Writing SQL query to check UNIQUE values on more columns.
- Writing a SQL check constraint for commission column.
- Adding check constraint using alter table statement
- Adding check constraints on multiple columns using AND,OR.

### Distinct where clause query ###
- Creating a table named Salesman with following columns Salesman_id, Name, City, Commission.
-  Selecting Salesman_id column as primary key and using identity for auto increment.
-  Writing a query for displaying all the records from salesmantable.
-  Using distinct clause to get the distinct name of the city
-  Using <> for getting all the city names except paris.
-  using wheere,AND fgetting the for getting the city records with commission>0.14 and city is paris.
-  Using order by for getting the records of the commission in ascending order. 
### Aggregate functions and Top clause ###
- Restored the database from AdventureworksDW2019.
- sorted the Lastname from the Dimcustomer table.
- Using the TOP clause to get the top 20 products from dimproduct table.
- using top and percent to get the 50 percentage of customers from DimCustomer table.
- Using the max and min functions to get the maximum and minimum yearly income from the DimCustomer.

### Union concept  ###
- Create dept. table with mentioned data and inserting values into it.
- Apply Join on Employee and Department tables using the common column DeptID.
- SQL query to display Dname, Avg. salary of Each dept. using Joins and Group by Clauses.
- Using AdventureWorksDW2019 database and Writing a SQL query to display FirstName and BirthDate and birthdate should be between 01-01-1985 to 01-12-1985 from DimCustomer and DimEmployee tables using Union and Union all functions. 

### Joins ###
- Create Employee_details table and ProjectDetail table and inserting values in to it.
- Getting employee name, project name order by firstname from "EmployeeDetail" and                 "ProjectDetail"     for those employee which have assigned project already. 
- Getting employee name, project name order by firstname from "EmployeeDetail" and                 "ProjectDetail"     for all employee even they have not assigned project. 
- Get all project name even they have not matching any employeeid, in left table, order by         firstname from "EmployeeDetail" and "ProjectDetail".
- Get complete record(employeename, project name) from both tables([EmployeeDetail],            [ProjectDetail]), if no match found in any table then show NULL.
 







