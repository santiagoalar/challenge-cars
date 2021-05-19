# challenge-cars

# CHALLENGE - CARS GAME BY CONSOLE - GROUP A #

## Summary ##

In this challenge we are going to model a car contest, where we are going to have certain rules of the game. For this challenge it is necessary to have the basic knowledge of Java / C \ # using the object-oriented programming paradigm. This implies knowing the modeling of objects, in addition, the results of the game must be saved in a database.

Within the challenge, the following should be considered:

 * Handling of classes or objects
 * Data persistence
 * Manage lists or collections
 * Knowledge of Java or C \ #
 * Git handling (control version)

  


Only apply to the challenge if you feel capable of doing it.

Good luck!

## Use Case / Problem ##

What is sought in this ** game ** is to create ** cars ** and position it on a ** track ** (each car has a ** driver **), there can be as many ** cars ** as * * lanes **, each track must have the same ** distance limit ** (kilometers) for the ** car ** route, the ** cars ** advance randomly ** increasing their ** distance ** by means of ** meters ** (the kilometers of must be converted to meters so that the advance is in meters)

  


Each advance must have a ** given ** (from 1 to 6) that allows the ** car ** to move and must be multiplied by 100, where if the die is rolled and you get 5 then it should be 5 \ * 100 = 500 meters of travel.

  


At the end there must be a ** podium ** where ** first **, ** second ** and ** third winner ** are classified.

  


## Features ##

  


 * ** Game Setup ** \: Create game with players, the game must have the limits of kilometers for each track (a player can be a driver and a driver must have an associated car and a car must be associated with a lane that turn must be on a track)
 * ** Start the game ** or: start with an identifier of the game, you must have the list of cars where you can iterate and advance according to the position of the track or lane, this must be random (by means of the dice).
 * ** Assign podium (end of game) ** \: First, second and third place must be selected as the cars reach the finish line (assign to podium).
 * ** Save data ** \: You must persist the results with the names of the drivers in the podium position and add a counter of the times they have won.

## Evaluation criteria ##

| Criteria | Percentage |
| -------------------------------------------------- -------------------------------------- | ---------- |
| Applies the principles of object-oriented programming | 31.0% |
| Make the persistence of the results obtained from the winners | 31.0% |
| Creation of entity objects; track, game, lane, cart, driver, player, podium | 30.0% |
| Methods with less than 6 lines of code | 8.0% |
