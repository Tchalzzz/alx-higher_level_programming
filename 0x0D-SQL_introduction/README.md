SQL - Introduction
This project contains some tasks for learning the basics about SQL using the MySQL DBMS.

Tasks To Complete
 0. List databases
0-list_databases.sql contains a script that lists all databases of the MySQL server.
 1. Create a database
1-create_database_if_missing.sql contains a script that creates the database hbtn_0c_0 in the MySQL server (if it doesn't exist).
 2. Delete a database
2-remove_database.sql contains a script that deletes the database hbtn_0c_0 in the MySQL server (if it exists).
 3. List tables
3-list_tables.sql contains a script that lists all the tables of a database in the MySQL server.
 4. First table
4-first_table.sql contains a script that creates a table called first_table in the current database in your MySQL server.
The description of first_table:
class first_table:
    id: INT
    name: VARCHAR(256)
 5. Full description
5-full_table.sql contains a script that prints the full description of the table first_table from the database hbtn_0c_0 in the MySQL server.
 6. List all in table
6-list_values.sql contains a script that lists all rows of the table first_table from the database hbtn_0c_0 in the MySQL server.
 7. First add
7-insert_value.sql contains a script that inserts a new row in the table first_table (database hbtn_0c_0) in the MySQL server.
The row:
{"id": 89, "name": "Best School"}
 8. Count 89
8-count_89.sql contains a script that displays the number of records with id = 89 in the table first_table of the database hbtn_0c_0 in the MySQL server.
 9. Full creation
9-full_creation.sql contains a script that creates a table second_table in the database hbtn_0c_0 in the MySQL server (if it doesn't exist), and adds multiples rows.
The description of second_table:
class second_table:
    id: INT
    name: VARCHAR(256)
    score: INT
The script should create these records:
[
  {"id": 1, "name": "John", "score": 10},
  {"id": 2, "name": "Alex", "score": 3},
  {"id": 3, "name": "Bob", "score": 14},
  {"id": 4, "name": "George", "score": 8}
]
 10. List by best
10-top_score.sql contains a script that lists all records of the table second_table of the database hbtn_0c_0 in the MySQL server. The records should be ordered by score (top first) and the results should display the score first then the name.
 11. Select the best
11-best_score.sql contains a script that lists all records with a score >= 10 in the table second_table of the database hbtn_0c_0 in the MySQL server. The records should be ordered by score (top first) and the results should display the score first then the name.
 12. Cheating is bad
12-no_cheating.sql contains a script that updates the score of Bob to 10 in the table second_table.
 13. Score too low
13-change_class.sql contains a script that removes all records with a score <= 5 in the table second_table of the database hbtn_0c_0 in the MySQL server.
 14. Average
14-average.sql contains a script that computes the score average of all records in the table second_table of the database hbtn_0c_0 in the MySQL server. The result column name should be average.
 15. Number by score
15-groups.sql contains a script that lists the number of records with the same score in the table second_table of the database hbtn_0c_0 in the MySQL server. The list should be sorted by the number of records (descending). The result should display the score first then the number of records for this score with the label number.
 16. Say my name
16-square.sql contains a script that lists all records of the table second_table of the database hbtn_0c_0 in the MySQL server. The results should display the score and the name (in this order) and they should be listed by descending score but rows without a name value shouldn't be included.
 17. Go to UTF8
100-move_to_utf8.sql contains a script that converts the following to UTF8 (utf8mb4, collate utf8mb4_unicode_ci) in the MySQL server:
Database hbtn_0c_0
Table first_table in database hbtn_0c_0
Field name in first_table
 18. Temperatures #0
101-avg_temperatures.sql contains a script that displays the average temperature (Fahrenheit) by city ordered by temperature (descending). The table in temperatures.sql is used for this task. The script in temperatures.sql should be executed using the database hbtn_0c_0, which should have been during the previous tasks, for testing tasks 18 to 20.
 19. Temperatures #1
102-top_city.sql contains a script that displays the top 3 of cities temperature during July and August ordered by temperature (descending).
 20. Temperatures #2
103-max_state.sql contains a script that displays the max temperature of each state (ordered by State name).
