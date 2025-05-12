# Reeborgs-World-4
## In this project, we have to get the robot to the end goal with the walls being different heights

<img width="607" alt="image" src="https://github.com/user-attachments/assets/7a3a52ab-c277-4831-9a02-ee151e6c0bca" />

```python
def turn_right():
    turn_left()
    turn_left()
    turn_left()
    
def jump():
    turn_left()
    while wall_on_right():
        move()
    turn_right()
    move()
    turn_right()
    while front_is_clear():
        move()
    turn_left()   
            
        
  # turn_left      
    
while not at_goal():
    if wall_in_front():
        jump()
   
    else:
        move()
