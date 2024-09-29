# Week 4
## Assignment 1

### Question 1
select country.name as "country name", airport.name as "airport name"
- from country inner join airport on airport.iso_country = country.iso_country
- where country.name = "Finland" and scheduled_service = "yes";

![Ex4_Q1.png](Week%203%2FExercise%204%2FEx4_Q1.png)
### Question 2
select screen_name, airport.name
- from game inner join airport on location = ident;

![Ex4_Q2.png](Week%203%2FExercise%204%2FEx4_Q2.png)
### Question 3
select screen_name, country.name
- from game inner join airport on location = ident inner join country on airport.iso_country = country.iso_country;

![Ex4_Q3.png](Week%203%2FExercise%204%2FEx4_Q3.png)
### Question 4
select airport.name, screen_name
- from airport left join game on ident = location where name like "%Hels%";

![Ex4_Q4.png](Week%203%2FExercise%204%2FEx4_Q4.png)
### Question 5
select name, screen_name
- from goal left join goal_reached on goal.id = goal_id  left join game on game.id = game_id;

![Ex4_Q5.png](Week%203%2FExercise%204%2FEx4_Q5.png)