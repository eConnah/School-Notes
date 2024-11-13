# Flat Files
Flat files are simple files that store data in plain text format without any structure. Each line in a flat file typically represents a single record, with fields separated by delimiters like commas or tabs. They are easy to create and read, but they can be challenging to manage as the data grows. They lack the ability to enforce data integrity, consistency, and relationships between different records.
The most common uses are for storing small to medium-sized datasets, such as CSV or TSV files.

## Normalisation
Normalisation is when you take a flat file and break it down into as many tables as possible. This is to make sure data is not duplicated in any fields. When you cant break it down any further its fully normalised.


### Importance of normalisation
The advantages of normalisation are that:
- It is easier to maintain and change a normalised database
- There is no unnecessary duplication of data
- Data integrity is maintained - if a person changes address, for example, the update needs to be made only once to a single table
- Having smaller tables with fewer fields means faster searches and savings in storage

### Normal Forms
- First Normal Form (1NF)
A table is in first normal form if it contains no repeating attribute or groups of attributes

- Second Normal Form (2NF)
A table is in second normal form if it is in first normal form and contains no partial dependencies. This can only occur if the primary key is a composite key.

- Third Normal Form (3NF)
A table is in third normal form if its in second normal form and contains no non-key dependencies. This means all attributes are dependent on the key itself.


# Relational Databases
Relational databases are structured databases that store data in tables, where each table consists of rows and columns. Each table has a unique name and is defined by a schema that specifies the column names, data types, and constraints. Relational databases provide a powerful mechanism for managing and organizing data through the use of relationships between tables. They enforce data integrity, consistency, and referential integrity, ensuring that the data stored is accurate and consistent. Relational databases offer powerful querying capabilities, allowing users to retrieve and manipulate data using SQL (Structured Query Language) statements. Relational databases are commonly used for managing large and complex datasets, where data integrity and consistency are crucial.

## Example
$$\text{Student}(\underline{\text{StudentID}}, \underline{\underline{\text{ParentID}}}, \underline{\underline{\text{SubjectID}}}, \text{Name, DOB})$$
$$\underline{\text{Primary Key}}$$
$$\underline{\underline{\text{Foreign Key}}}$$

Composite primary key, sometimes two or even more attributes are needed to uniquely define a record. For example, in a customer order consisting of many different order lines, each order line may be uniquely identified by the two attributes orderNumber and orderLine.