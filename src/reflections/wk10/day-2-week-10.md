# What is the difference between a primary key and a foreign key
A primary is the main unique key on the table, a foreign key will reference the primary key from another table.
# What is an Alias?
It lets you shorten the name of the and assign other names to it as well

# Demonstrate how you would query a join statement that would get all of a doctors patients from the following collections:

SELECT p.*, d  as p.id patientid
JOIN patients p ON p.id = d.i