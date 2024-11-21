# n-puzzle

in this lab there is the implementation of 2 studied methods, the breadth first and the A*.

For the A* we have implemented three different function to introduce some rules or intelligent behaviour, the proper functions are h(x), g(x), k(x).
The function h(x) should be fixed, anyway was working. 
In the code there are different experiment based on N, that is the dimension of the n-puzzle.
In script there are the lines comment that describe the macro-behaviour of my implementation ( mainly for the function h(x), g(x), k(x) that are more customize)
The results are summarize in the following table.

| N  | Breadth-First |  A* - k(x) | A* - g(x)  | 
|----------|----------|----------|----------|
| 2 | (step - #states) (3, 5) | (step - #states) (1, 1) | (step - #states) (5, 12) |
| 3 | (step - #states) (27, 172110) | (step - #states) (31, 3704) | (step - #states) (41, 85738) |
| 4 |  | | |
