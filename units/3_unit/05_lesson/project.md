# Project 3: Oregon Trail

Using variables, functions, and conditionals in Python, students will create an Oregon Trail game. 

## Overview
We will be recreating Oregon Trail! The goal is to travel from NYC to Oregon (2000 miles) by Dec 31st. However, the trail is arduous. Each day costs you food and health. You can hunt and rest, but you have to get there before winter! 

## Details 
### Behavior 
* Player starts in NYC on 03/01 with 2,000 miles to go, 500lbs of food, and 5 health. 
* The player must get to Oregon by 12/31
* At the beginning of the game, user is asked their name.
* Each turn, the player is asked what action they choose, where the player can type in the following: `travel`, `rest`, `hunt`, `status`, `help`, `quit`
* The player's health randomly decreases 2 times during the month. 
* `travel`: moves you randomly between 30-60 miles and takes 3-7 days (random).
* `rest`: increases health 1 level (up to 5 maximum) and takes 2-5 days (random).
* `hunt`: adds 100 lbs of food and takes 2-5 days (random).
* `status`: lists food, health, distance traveled, and day.
* `help`: lists all the commands.
* `quit`: will end the game.

### Implementation details 
* Create functions for all options a player can take, each function should take in a a list of user_data
* Create a list of variables called user_data that will contain the health, food, miles, month, day, days_passed, and more and be passed to each function
* Create a function add_day which updates the day and takes in the list of user_data
* Create a function update_days which uses a while loop to call add_day function and takes in the list of user_data

## Grading 
### Scheme/Rubric
| **Functional Correctness(Behavior)**                                |     |
| --------------------------------------------------------------- |-----|
| `travel`, `rest`, `hunt`                                        | 30  |
| `status`, `help`, and `quit`                                    | 15  |
| Game ends if food runs out, days run out, or health runs out    | 20  |
| Days roll over correctly	                                       | 15  | 
| Helth decreases randomly	                                       | 5   | 
| **Sub total**                                                   | 90  |
| **Technical Correctness   **                                    |     |
| Correctly use functions and contracts                           | 35  |
| Correctly use imported random function                          | 10  |
| Correctly use and update varaiables                             | 10  |
| Correctl add_days and update_days functions                     | 20  |
| **Sub total**                                                   | 75  |
| **Total**                                                       | 165 |


