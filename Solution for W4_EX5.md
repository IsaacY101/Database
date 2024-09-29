# Week 4
## Assignment 2

### Question 1
select name
- from country 
- where iso_country in(select iso_country from airport where name like "Satsuma%");

![Ex5_Q1.png](Week%203%2FExercise%205%2FEx5_Q1.png)
### Question 2
select name
- from airport where iso_country in( select iso_country
- from country where name = "Monaco");

![Ex5_Q2.png](Week%203%2FExercise%205%2FEx5_Q2.png)
### Question 3
select screen_name
- from game
- where id in ( select game_id from goal_reached where goal_id in (select id from goal where name = "CLOUDS"));

![Ex5_Q3.png](Week%203%2FExercise%205%2FEx5_Q3.png)
### Question 4
select country.name
- from country
- where iso_country not in (select airport.iso_country from airport);

![Ex5_Q4.png](Week%203%2FExercise%205%2FEx5_Q4.png)
### Question 5
select name
- from goal
- where id not in(select goal.id from goal, goal_reached, game where game.id = game_id and goal.id = goal_id and screen_name = "Heini");

![Ex5_Q5.png](Week%203%2FExercise%205%2FEx5_Q5.png)