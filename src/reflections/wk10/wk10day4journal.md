In a SQL table, what is the difference between information in a row and information in a column?

Rows are complete objects and columns are are specific properties.

Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.

--  CREATE TABLE characters
--  (
--    id INT AUTO_INCREMENT,
--    name VARCHAR(255) NOT NULL UNIQUE,
--    age INT,
--    description STRING,
--    PRIMARY KEY (id)
--  ); 


What is the difference between the following statements:
(
DELETE FROM table_name: This deletes the content that's in the table.

DROP TABLE table_name: This actually drops or "deletes" the whole table itself. 
)


https://github.com/KalebMcElyea/CastlesC-