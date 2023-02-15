SQL - More queries
sqlstyle.guide

This project contains some tasks for learning more about the basics of SQL using the MySQL DBMS.

Tasks To Complete
 0. My privileges!
0-privileges.sql contains a script that lists all privileges of the MySQL users user_0d_1 and user_0d_2 on the MySQL server.
 1. Root user
1-create_user.sql contains a script that creates the MySQL server user user_0d_1 with all privileges and the password user_0d_1_pwd in the MySQL server (if it doesn't exist).
 2. Read user
2-create_read_user.sql contains a script that creates the database hbtn_0d_,2 and the user user_0d_2 with only SELECT privileges and the password user_0d_2_pwd in the MySQL server (if they don't exist).
 3. Always a name
3-force_name.sql contains a script that creates the table force_name in the MySQL server (if it doesn't exist).
The description of force_name:
class force_name:
    id: INT
    name: VARCHAR(256)
name cannot be null.
 4. ID can't be null
4-never_empty.sql contains a script that creates the table id_not_null in the MySQL server (if it doesn't exist).
The description of id_not_null:
class id_not_null:
    id: INT
    name: VARCHAR(256)
id has a default value of 1 and name cannot be null.
 5. Unique ID
5-unique_id.sql contains a script that creates the table unique_id in the MySQL server (if it doesn't exist).
The description of unique_id:
class unique_id:
    id: INT
    name: VARCHAR(256)
id has a default value of 1 and must be unique. name cannot be null.
 6. States table
6-states.sql contains a script that creates the database hbtn_0d_usa and the table states (in the database hbtn_0d_usa) in the MySQL server (if they don't exist).
The description of states:
class states:
    id: INT
    name: VARCHAR(256)
id has a to be unique, auto generated, not null and must be the primary key. name cannot be null.
 7. Cities table
7-cities.sql contains a script that creates the database hbtn_0d_usa and the table cities (in the database hbtn_0d_usa) in the MySQL server (if they don't exist).
The description of cities:
class cities:
    id: INT
    state_id: INT
    name: VARCHAR(256)
id has a to be unique, auto generated, not null and must be the primary key. state_id must be a FOREIGN KEY that references to id of the states table and cannot be null. name cannot be null.
 8. Cities of California
8-cities_of_california_subquery.sql contains a script that lists all the cities of California that can be found in the database hbtn_0d_usa in the MySQL server. The results must be sorted in ascending order by cities.id and the JOIN keyword should not be used.
 9. Cities by States
9-cities_by_state_join.sql contains a script that lists all cities contained in the database hbtn_0d_usa. Each record should display: cities.id - cities.name - states.name (in that order). The results must be sorted in ascending order by cities.id and only one SELECT statement can be used.
 10. Genre ID by show
10-genre_id_by_show.sql contains a script that lists all shows contained in hbtn_0d_tvshows that have at least one genre linked. Each record should display: tv_shows.title - tv_show_genres.genre_id (in that order). The results must be sorted in ascending order by tv_shows.title and tv_show_genres.genre_id. Only one SELECT statement can be used. The script in hbtn_0d_tvshows.sql should be executed using the database hbtn_0d_tvshows, which should be created for testing tasks 10 to 18.
 11. Genre ID for all shows
11-genre_id_all_shows.sql contains a script that lists all shows contained in the database hbtn_0d_tvshows. Each record should display: tv_shows.title - tv_show_genres.genre_id (in that order). The results must be sorted in ascending order by tv_shows.title and tv_show_genres.genre_id. If a show doesn’t have a genre, display NULL. Only one SELECT statement can be used.
 12. No genre
12-no_genre.sql contains a script that lists all shows contained in hbtn_0d_tvshows without a genre linked. Each record should display: tv_shows.title - tv_show_genres.genre_id (in that order). The results must be sorted in ascending order by tv_shows.title and tv_show_genres.genre_id. Only one SELECT statement can be used.
 13. Number of shows by genre
13-count_shows_by_genre.sql contains a script that lists all genres from hbtn_0d_tvshows and displays the number of shows linked to each. Each record should display: <TV Show genre> - <Number of shows linked to this genre> (in that order). The first column must be called genre. The second column must be called number_of_shows. A genre that doesn’t have any shows linked shouldn't be displayed. The results must be sorted in descending order by the number of shows linked. Only one SELECT statement can be used.
 14. My genres
14-my_genres.sql contains a script that uses the hbtn_0d_tvshows database to list all genres of the show Dexter. Each record should display: tv_genres.name. The results must be sorted in ascending order by the genre name. Only one SELECT statement can be used.
 15. Only Comedy
15-comedy_only.sql contains a script that lists all Comedy shows in the database hbtn_0d_tvshows. Each record should display: tv_shows.title. The results must be sorted in ascending order by the show title. Only one SELECT statement can be used.
 16. List shows and genres
16-shows_by_genre.sql contains a script that lists all shows, and all genres linked to that show, from the database hbtn_0d_tvshows. If a show doesn’t have a genre, display NULL in the genre column. Each record should display: tv_shows.title - tv_genres.name (in that order). The results must be sorted in ascending order by the show title and genre name. Only one SELECT statement can be used.
 17. Not my genre
100-not_my_genres.sql contains a script that uses the hbtn_0d_tvshows database to list all genres not linked to the show Dexter. Each record should display: tv_genres.name. The results must be sorted in ascending order by the genre name. Only a maximum of two SELECT statements can be used.
 18. No Comedy tonight!
101-not_a_comedy.sql contains a script that lists all shows without the genre Comedy in the database hbtn_0d_tvshows. Each record should display: tv_shows.title. The results must be sorted in ascending order by the show title. Only a maximum of two SELECT statements can be used.
 19. Rotten tomatoes
102-rating_shows.sql contains a script that lists all shows from hbtn_0d_tvshows_rate by their rating. Each record should display: tv_shows.title - rating sum (in that order). The results must be sorted in descending order by the rating. Only one SELECT statement can be used. The script in hbtn_0d_tvshows_rate.sql should be executed using the database hbtn_0d_tvshows_rate, which should be created for testing tasks 19 and 20.
 20. Best genre
103-rating_genres.sql contains a script that lists all genres in the database hbtn_0d_tvshows_rate by their rating. Each record should display: tv_genres.name - rating sum (in that order). The results must be sorted in descending order by their rating. Only one SELECT statement can be used.
