# Flat Files
Flat files are simple files that store data in plain text format without any structure. Each line in a flat file typically represents a single record, with fields separated by delimiters like commas or tabs. They are easy to create and read, but they can be challenging to manage as the data grows. They lack the ability to enforce data integrity, consistency, and relationships between different records.
The most common uses are for storing small to medium-sized datasets, such as CSV or TSV files.

# Relational Databases
Relational databases are structured databases that store data in tables, where each table consists of rows and columns. Each table has a unique name and is defined by a schema that specifies the column names, data types, and constraints. Relational databases provide a powerful mechanism for managing and organizing data through the use of relationships between tables. They enforce data integrity, consistency, and referential integrity, ensuring that the data stored is accurate and consistent. Relational databases offer powerful querying capabilities, allowing users to retrieve and manipulate data using SQL (Structured Query Language) statements. Relational databases are commonly used for managing large and complex datasets, where data integrity and consistency are crucial.

## Example
$$\text{Student(\underline{StudentID}, \underline{\underline{ParentID}}, \underline{\underline{SubjectID}}, Name, DOB)}$$
$$\text{\underline{Primary Key}}$$
$$\text{\underline{\underline{Foreign Key}}}$$

Composite primary key, sometimes two or even more attributes are needed to uniquely define a record. For example, in a customer order consisting of many different order lines, each order line may be uniquely identified by the two attributes orderNumber and orderLine.