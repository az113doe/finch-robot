# Goals for finch robots:
| Sucess  | Aim | Progress |
| ------- | --- | -------- |
| Okay    | Familarize with Finch Robot | 75% |

## Intentions: 
Finch robot to move around with user input

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

## End Result:
The end result should be moving forward and backward. However, the end result I want would be for A and D, to turn the robot and have it also move
