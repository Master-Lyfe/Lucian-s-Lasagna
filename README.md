# Lucian-s-Lasagna 
An Exercism Exercise in JavaScript

Introduction
--

Create a time management program
* Everything is to calculated in minutes 
* Use givens
* Help friend stay on time to save relationshhip

Givens:
-
* EXPECTED_MINUTES_IN_OVEN = 40
* remainingMinutesInOven 
* preparationTimeInMinutes
* each layer takes you 2 minutes to prepare
* totalTimeInMinutes
* numberOfLayers
* actualMinutesInOven



Tasks to create and master:
--

1 ) Define Oven time for meal
- How much time is expeected to cook this meal?
- Is this constant or will this time vary?
- Should this number be used in other functiond?

2 ) Calculate remaining oven time 
- Whats the bondaries?
- What do ew expect for output?
- GOAL: function that takes the actual minutes the lasagna has been in the oven as a parameter and returns how many minutes the lasagna still has to remain in the oven, based on the expected oven time in minutes from the previous task

3 ) calculate prep time
- How much time is expected to prepin total?
- Why did we chose our parameers?

4 ) Calculate working time total
- the numberOfLayers parameter is the number of layers you added to the lasagna
- The function should return how many minutes in total you've worked on cooking the lasagna, which is the sum of the preparation time in minutes, and the time in minutes the lasagna has spent in the oven at the moment

5 ) WriteUp what you found while exploring?
- Why were these concepts worthy of the firt problem solving lesson?
- How has my undestanding changed?



GIVEN CODE SAMPLES:
--

remainingMinutesInOven(30);
// => 10

preparationTimeInMinutes(2);
// => 4

totalTimeInMinutes(3, 20);
// => 26
