# In a SQL table, what is the difference between information in a row and information in a column?
Single instances are stored in a row.
While multiple things are stored in a column

# Demonstrate the basic structure for creating a new table called characters with the values name, age, description as strings, and an int id.
CREATE TABLE characters(
    id int not null,
    name VARCHAR,
    age int,
    description VARCHAR,

)

# What is the difference between the following statements:
DELETE FROM table_name;
DROP TABLE table_name;

Drop table will delete the whole thing where as Delete from will delete an individual thing