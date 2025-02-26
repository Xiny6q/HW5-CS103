Download link :https://programming.engineering/product/hw5-cs103


# HW5-CS103
HW5 CS103
Instructions

To work on HW5:

build a HW5directory under your home directory (cs103sp22)

start Jupyter Notebook and from dashboard navigate to hw5 folder

create hw5.ipynb in hw5 folder

in the notebook, create the myName and myBlazerID functions which returns your name and your blzerid (the same function you had in hw1)

Create docstrings for each function (-2 points for each missing docstrings)

once you are confident that your code works, submit on Canvas



Mandatory Functions

The following functions should be implemented, and the return statements should be modified with the correct credentials. Do not forget to call the functions

def myName():

return “James Bond”

def myBlazerID():

return “jbon12”

# Call these functions

print(“My Name is =”, myName(), “ and my BlazerId is =”,myBlazerID())

CS103 Spring Homework 5 Page 1 of 2

Objectives:

Turtle Graphics

Create the necessary helper functions to solve the problem below.

Homework Instructions

We will implement a Python Turtle program that randomly chooses a shape from the list below, generate a random color, and define a random size to draw it on random location of the screen.

Here are the shapes that you should randomly choose from:

Square (each side is n pixel)

Circle (radius is n pixel)

Rectangle (width= 2*n pixel, height=n pixel)

Equilateral Triangle (each side is n pixel)

Regular Pentagon (each side is n pixel)

For each run:

your code should choose a random shape from the list above [25 points]

generate a random integer value for n value (for each n à 25<n<100) [25 points]

generate a random color to fill in the shape; use RGB color system (Hints: generate three random int between 0 and 255) [25 points]

Generate a random location to start drawing your shape (random x and y coordinate values, make sure you limit them to fit on the screen) [25 points]

Example runs:

Rectangle (80×40), color(200,125,58), location(x=35,y=-10)

Circle (r=12), color (0,32,55), location (-15,36)

Deliverables: hw5.ipynb and independent_completion_form



Bonus Points: Random color for the shape (the drawings not to fill in) +10 points Random star shape, each side is n pixel, +10 points

CS103 Spring Homework 5 Page 2 of 2
