Your assignment for this week is to create two functions that expand the range of available turtle behaviours. You are welcome to work on your functions in the development environment of your choice. Your functions should make creative use of the coding concepts we've discussed in class including variables, loops and functions. When designing your functions please pay attention to the function parameters and the use of local variables in order to maximize the portability of the function. Your functions can make use of one turtle or many turtles.

Your submission should include 1) images illustrating the graphical result of running each of your functions; 2) your Python code and comments captured in a Jupyter notebook. If you don't use a Jupyter notebook to develop and test your code, you will need to paste the code into a notebook and add comments.

Here are some suggestions for functions you could write:

- Create an 'emergent circle' by implementing the following steps:
    Randomly place multiple turtles on the screen.
    Orient all turtles toward a common point.
    Instruct all turtles to move forward or backward in order to reach a given distance from the common point.
  
- Create two types of turtle behaviour: 'targets' that repel or attract the other turtles, and 'worker' turtles that move toward or away from the targets. What pattern results if the 'worker' turtles seek out a position equidistant from the two nearest targets?

- What happens if you have only one 'target' turtle in the above scenario? What is the resulting form?

- Create a random movement behaviour for turtles. How can this random movement be refined through adjustment of parameters?

- Introduce collision detection between randomly moving turtles.

- Introduce a bounding region (or multiple bounding regions) within which the randomly moving turtles are confined.

- Write a function that draws a line between every turtle and its nearest neighbour.

You may find it helpful to look at the documentation for the turtle.distance, turtle.heading, and turtle.towards functions. 
