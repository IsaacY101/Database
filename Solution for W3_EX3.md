# Week 3
## Assignment 2

### Question 1
select country.name as "country name", airport.name as "airport name"
- from airport, country
- where airport.iso_country = country.iso_country and country.name = "Iceland";

![EX3_Q1.png](Week%203%2FExercise%203%2FEX3_Q1.png)
### Question 2
select airport.name as "airport name"
- from airport, country
- where airport.iso_country = country.iso_country and country.name = "France" and airport.type = "large_airport";

![EX3_Q2.png](Week%203%2FExercise%203%2FEX3_Q2.png)
### Question 3
select country.name as country_name, airport.name as airport_name
- from airport, country
- where airport.iso_country = country.iso_country and country.continent = "AN";

![EX3_Q3.png](Week%203%2FExercise%203%2FEX3_Q3.png)

### Question 4
select elevation_ft
- from airport, game
- where location = ident and screen_name = "Heini";

![EX3_Q4.png](Week%203%2FExercise%203%2FEX3_Q4.png)
### Question 5
 select elevation_ft * 0.3048 as elevation_m
 - from airport, game
 - where location = ident and screen_name = "Heini";

![EX3_Q5.png](Week%203%2FExercise%203%2FEX3_Q5.png)
### Question 6
 select name
 - from airport, game
 - where location = ident and screen_name = "Ilkka";

![EX3_Q6.png](Week%203%2FExercise%203%2FEX3_Q6.png)
### Question 7
select country.name
- from airport, game, country
- where location = ident and airport.iso_country = country.iso_country  and screen_name = "Ilkka";
![EX3_Q7.png](Week%203%2FExercise%203%2FEX3_Q7.png)
### Question 8
select name
- from goal, goal_reached, game
- where game.id = game_id and goal.id = goal_id and screen_name = "Heini";

![EX3_Q8.png](Week%203%2FExercise%203%2FEX3_Q8.png)
### Question 9
 select airport.name
 - from airport, game, goal, goal_reached
 - where ident = location and game.id = game_id and goal.id = goal_id and screen_name = "Ilkka" and goal.name = "CLOUDS";

![EX3_Q9.png](Week%203%2FExercise%203%2FEX3_Q9.png)
### Question 10
select country.name
- from country, airport, game, goal, goal_reached
- where airport.iso_country = country.iso_country and ident = location and game.id = game_id and goal.id = goal_id and screen_name = "Ilkka" and goal.name = "CLOUDS";

![EX3_Q10.png](Week%203%2FExercise%203%2FEX3_Q10.png)

