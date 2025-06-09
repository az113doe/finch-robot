# Goals for finch robots:
| Sucess  | Aim | Progress |
| ------- | --- | -------- |
| Sucessful  | Familarize with Finch Robot | 95% |
| Sucessful  | Developement of code for user input movement | 90% |

## My Motivation:
The movement of the finch robot interested me the most, and with the user inputted movement compeleted, it become a strong foundation for additional code later on

## Uniqueness: 
The user input, should allow the finch robot to feel like a control race car

## Design Cycle
![alt text](https://github.com/hansTeachesCS/finch-robot/blob/main/design_cycle.png)

## Approach:
- Usage of Scanner to detect user input
- Conditional Statements (WASD) for the movement
- W - Forward
- S - Backward
- A - Turn Left
- D - Turn Right
- Calling the setMove and setTurn methods from finch.java class

## Highlight Code:
```
if (input.equals("W")) {Add commentMore actions
				finch.setMove("F", 10, 50);
			} else if (input.equals("A")) {
				finch.setTurn("L", 90, 50);
			} else if (input.equals("S")) {
				finch.setMove("B", 10, 50);
			} else if (input.equals("D")) {
				finch.setTurn("R", 90, 50);
			}
```

## End Result & What I learned:
The robot moves using WASD input like most video games. It similar to the movement of snake.
Overall, experimenting and familarizing myself with the finch robot thought help me further enhance my views of the design cycle, it a process that I was using during science research in SRMP, but certain part like **create** and **improve** were often gloss over

## Future prospect:
In the future, with more time experimenting on the finch robot, hopefully the control can expand from North, South, West, East to having diagonal movements. Additional, having the robot turn left (180 degrees) when it facing right
