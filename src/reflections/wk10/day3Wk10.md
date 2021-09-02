In a SQL table, what is the difference between information in a row and information in a column?

The info in the row is pertaining to the specific object, where as the info in the column is a place for data belonging to each row.

Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

CREATE TABLE Characters (
    CharacterID int,
    LastName varchar(255),
    FirstName varchar(255),
    Age int,
    Description varchar(255)
);

What is the difference between the following statements:
DELETE FROM table_name;
DROP TABLE table_name;

DROP would remove all info and couldn't be recovered. The DELETE allow you to delete an item from the table but leaves the column structure intact

Afternoon: Still sick at home. Struggled with powershell until I gave up and read through the Foundations of C# and the SQL. Sidenote - It should totally be a rule that if you're sick you can't come into codeworks. If it was policy I wouldn't be feeling like death atm, and unable to focus, just saying