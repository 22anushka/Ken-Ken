# Ken-Ken

KenKen is an arithmatic and logical puzzle which shares similarities with Sudoku. The grid is divided into heavily outlined groups ofcells called ‘cages’ such that the numbers in the cells of each cage must produce a certain “target” number when combined using a specified mathematical operation
(one of addition, subtraction, multiplication or division).

Example of pygame board: 

![example 4x4](https://github.com/22anushka/Ken-Ken/blob/main/KenKen%20images/KenKen%20example.bmp)

Following are some rules and instructions that are to be followed while solving the puzzle:
1. Fill in each square cell in the puzzle with a number between 1 and the size of
the grid.
2. No numbers may repeat in any row or column.
3. The numbers in each “Cage” must combine — in any order — to produce the
cage’s target number using the indicated math operation. Numbers may be
repeated within a cage as long as rule 2 isn’t violated.
4. A cage with one square is a “Freebie” that should be filled in with the target
number in the top corner.

Solution to the example:

![example 4x4](https://github.com/22anushka/Ken-Ken/blob/main/KenKen%20images/KenKen%20solution.bmp)
The puzzle has been solved using AI with the concept of Constraint Satisfaction Problem by implementing domain reduction and backtracking to find the appropriate solution.
It has been demonstrated with the help of a GUI constructed using pygame.

![Alt Text](https://github.com/22anushka/Ken-Ken/blob/main/KenKenSolved.gif)

[KenKen](http://www.kenkenpuzzle.com/)
