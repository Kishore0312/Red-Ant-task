# Sudoku Validator

### Language Used - Python3 (version 3.8)
### Tools Used - IDLE, COLAB
### Uploaded files info

1. annotated_board.py - This file defines the functions and conditions of suduko
2. Question_3.ipynb - This file defines with DFS search algorithm for puzzles where a solution can't be solved solely via deduction. It shows the output of the given input file. i.e., this code runs the text files and provides the solution.
3.  Input1.sudoku, empty.sudoku - These are the input files. i.e., Input1.sudoku is a intermediate level existing puzzle and empty.sudoku is an empty 9*9 where the code itself produces own optimized solutions. The code produces random output solution for empty.sudoku file. In the input file, the unfilled spaces are defined in '.(dot)' format.

## Functions
### Important functions:

1. self.__init__(self, board=None): Initialize a blank puzzle or use an AnnotatedBoard to make a copy.
2. self.__repr__(self): for interactive interpreters. displays in Type(known, completed, validity) format.
3. self.__str__(self): convert the board to a print pretty format for use with print() function. i.e.,

game = AnnotatedBoard()
game.from_file('hard1.sudoku')
game = DFS(game)
print(game)
5 1 9 | 7 4 8 | 6 3 2
7 8 3 | 6 5 2 | 4 1 9
4 2 6 | 1 3 9 | 8 7 5
------+-------+------
3 5 7 | 9 8 6 | 2 4 1
2 6 4 | 3 1 7 | 5 9 8
1 9 8 | 5 2 4 | 3 6 7
------+-------+------
9 7 5 | 8 6 3 | 1 2 4
8 3 2 | 4 9 1 | 7 5 6
6 4 1 | 2 7 5 | 9 8 3

## Screenshots

1. Empty Input
![emptyinput](https://user-images.githubusercontent.com/59074144/116353415-5abbc700-a814-11eb-82ad-24553e3a67c4.png)

2. Input1 
![Input1](https://user-images.githubusercontent.com/59074144/116353552-9a82ae80-a814-11eb-81b5-26b697a34c49.png)

3. Output (for empty.sudoku)
![Output_empty1](https://user-images.githubusercontent.com/59074144/116353958-55ab4780-a815-11eb-9002-48f476075e04.png)


