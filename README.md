# Welcome to My Spaceship
***

## Task
i am to create a Spaceship stimulator that takes in strings which represents it flight path and return the format as x: X, y: Y, direction: Direction.
x and y representing the ending coordinate an direction represents it final direction.  
the movement of the ship will be to turn right which will be reprsented by "R", then turn left reprsented by "L", and lastly Advance reprsented by "A"
i will return the x and y cordinate of the spaceship final destination as well as the orientation relative to the starting point, the orientationis represented by left, right up and down.

## Description
first i declared a function called my spaceship with the parameter named flightPath, then i declared a variable called pathLenght which is equal to flightPath.pathLenght
i declared that store the x axis direction, y axis direction and another variable that store the position the spaceship is facing.
i initialize the x variable to 0, y variable to 0 as well and the positionthe spaceshipis facing to up.
i used the for to loop through the string to get each character from the string.
i used the switch statement to check the expression againts multiple cases. the cases are three cases
for case 'L' the code is if the current direction is up and you enter 'L' the ship faces left, else if it is left it will face down, else if it is down it will face right, and lastly, else if it is right it will face up.
for the case 'R' the code is if the current direction is up and you enter 'R' the ship faces right, else if it is right it will face down, else if it is down it will face left, and then else if it is right it will face down.
for the case 'A'  which is the advance, if the current direction is up it will decrement y(Y--), else if it is right it will increment x(X++), else if it is down it will increment x(x++), else if it is left it will decrement x(x--).
## Installation
i have not yet gotten to the part where i need Installation.

## Usage
i have not yet gotten to the part where i need usage.

### The Core Team


<span><i>Made at <a href='https://qwasar.io'>Qwasar SV -- Software Engineering School</a></i></span>
<span><img alt='Qwasar SV -- Software Engineering School's Logo' src='https://storage.googleapis.com/qwasar-public/qwasar-logo_50x50.png' width='20px'></span>
