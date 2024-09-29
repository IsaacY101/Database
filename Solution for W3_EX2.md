# Week 3
## Assignment 1

### Question 1,
Select from goal;
![Ex2_Q1.png](Week%203%2FExercise%202%2FEx2_Q1.png)
###  Question 2
Select name,type 
- *from airport 
- where iso_country = 'FI'
- order by type;

![Ex2_Q2-1.png](Week%203%2FExercise%202%2FEx2_Q2-1.png)
### Question 3
Select name 
- From airport,
- Where iso_country = "FI"
- Order by name;

![Ex2_Q3.png](Week%203%2FExercise%202%2FEx2_Q3.png)
### Question 4
Select name, type 
- From airport
- Where iso_country ='FI'
- Order by type, name;

![Ex2_Q4-1.png](Week%203%2FExercise%202%2FEx2_Q4-1.png)
### Question 5
Select name 
- From country
- Where name LIKE 'F%';

![Ex2_Q5.png](Week%203%2FExercise%202%2FEx2_Q5.png)
### Question 6
Select name 
- From country
- Where name LIKE '%F%';

![Ex2_Q6.png](Week%203%2FExercise%202%2FEx2_Q6.png)
### Question 7
Select location 
- From game
- Where screen_namr = 'Vesa';

![Ex2_Q7.png](Week%203%2FExercise%202%2FEx2_Q7.png)
### Question 8
Select c02_consumed 
- From game
- Where Screen_name = 'Ilkka';
![Ex2_Q8.png](Week%203%2FExercise%202%2FEx2_Q8.png)
### Question 9
Select co2_budget 
- From game
- Limit 1;

![Ex2_Q9.png](Week%203%2FExercise%202%2FEx2_Q9.png)
### Question 10
Select screen_name, co2_budget, co2_consumed, co2_budget - co2_consumed AS co2_left 
- From game
- where screen_name = 'Ilkka'
![Ex2_Q10.png](Week%203%2FExercise%202%2FEx2_Q10.png)