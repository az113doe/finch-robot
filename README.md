# Goals for finch robots:
| Sucess  | Aim | Progress |
| ------- | --- | -------- |
| Okay    | Familarize with Finch Robot | 75% |
| Almost  | Developement of code for user input movement | 85% |

## My Motivation:
The movement of the finch robot interested me the most, and with the user inputted movement compeleted, it become a strong foundation for additional code later on

## Uniqueness: 
The user input, should allow the finch robot to feel like a control race car

## Design Cycle
<img src="[images/example.png](https://res.cloudinary.com/monday-blogs/w_1200,h_1200,c_fit/fl_lossy,f_auto,q_auto/wp-blog/2021/02/Design-process-diagram.png)" width="300" />

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
(To be finished at the end)
