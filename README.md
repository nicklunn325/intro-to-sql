# Intro to SQL

Tools:

- SQLite3 => C-Language library SQL database engine
- SQLite => VSCode extension for viewing and interacting with SQLite databases
- chinook.db => a sample database created by Microsoft

  [Chinook DB download](https://sqlitetutorial.net/sqlite-sample-database)

## What is SQL?

Sturctured Query Language
a language used to communicate with databases

## What is a database?

used to stored or persist data
a series of tables

## different types of DBs

    - Relational databases
    allow us to represent relationships between tables through the use of foreign keys
    - Non Relational databases

## What is SQL used for?

    - interacting with our DB
    Insert (create)
    Select (read)
    Update
    Delete

    CRUD

## How to make SQL queries

## SQLite3 tips:

to run the default sqlite terminal:
sqlite3

to run the sqlite terminal with a database:
sqlite3 <chinook.db>

to run a sql query on a database:
sqlite3 <chinook.db> < <file.sql>

## Relational Databases

## SQL Queries

1. Write a SQL Query to select all the rows in the artists table

2. Write a SQL Query to select the artist with the name "Black Sabbath"

3. Write a SQL Query to create a table named "fans" with an auto-incrementing ID that's a primary key and a name field of type text

4. Write a SQL Query to alter the fans table to have an artistId column of type integer

5. Write a SQL Query to add yourself as a fan of the Red Hot Chili Peppers ArtistId **_127_**

6. Write a SQL Query to change your "name" in the fans table.

7. Write a SQL Query to return all the fans that not fans of the Black Eyed Peas(169)

8. Write a SQL Query to display artist name, album name, and number of tracks on that album

9. Write a SQL Query to return the name of all of the artists in the 'Pop' Genre

[SQLite vs MySQL vs PostgreSQL](https://www.digitalocean.com/community/tutorials/sqlite-vs-mysql-vs-postgresql-a-comparison-of-relational-database-management-systems)
