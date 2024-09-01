
## Snake Game

This is the well known Snake Game which we used to play during our childhood, the nokia 3310 was everyones dream during 90's .
 
 
## Demo

here is a Demo Video of my Snake Game.

https://www.linkedin.com/posts/rohit-wankhede-453b021b9_snakegame-python-github-activity-7235928104068673536-tHlp?utm_source=share&utm_medium=member_desktop


## Documentation
steps for snake Project:
1) Create snake body:  
    first we have created 3 basic segments of the snake body.
2) Move the snake:  
    to move the snake we have applied some logic.
    the third segment will take the position of second             segment and second segment will take the position of first segment.
    hence when the different direction given to the first segment, the remaining segments follow the first.

3) Control the snake:
snake is Controlled by the key (up, down, left, right)
to use this you must go through the turtle Documentation.

4) Detect collision with food
we have created a inheritance from the superclass
which gives an advantage to use its methods.
after collision with food snake must extend at end of tail

5) Create scorebordwe :
we follow same procedure for scorecard like food

6) Detect collision with wall
when the head of snake comes near to boundry of wall game must be over

7) Detect collision with tail
follow same for the tail except the first segment i.e head

moving step by step is the key for any project.


here are some Documentation links you can use to explore.

https://docs.python.org/3/library/turtle.html#introduction



