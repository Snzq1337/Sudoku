# Sudoku
A Simple Sudoku Solver

### The Past

I wrote a very simple Sudoku solver a couple years ago. My friends introduced me to the puzzle and spent their lunchtimes solving them. I solved one or two by hand and realized that I would enjoy writing a program to solve them rather than solving them myself.

That early version of the program could only handle simple sudoku puzzles that didn’t involve guessing and backtraking. Unfortunately that early version has been lost in the mists of time.

### The Present

This new version of the solver was written from scratch and does handle tougher puzzles the require guessing and backtracking. Except for the puzzle parsing code, it doesn’t share any implementation with my friend's solution.

### Usage

Just pass it the name of the puzzle file (.sud) on the command line. It will print out the initial and final puzzles, and each step along the way to a solution.

Example:

*ruby sudoku.rb puzzles/evil.sud*

