# N-Queen problem using Backtracking
Solving N-Queen problem using backtracking

The aim of N-Queens Problem is to place N queens on an N x N chessboard, in a way so that no queen is in conflict with the others.

### Backtracking (a.k.a Depth First Search)
The idea is to place queens one by one in different columns, starting from the leftmost column. When we place a queen in a column, we check for clashes with already placed queens. In the current column, if we find a row for which there is no clash, we mark this row and column as part of the solution. If we do not find such a row due to clashes then we backtrack and return false.

The following image shows one of the solutions of a 4-Queen problem using backtracking. If the image does not suffice, you may want to watch [this](https://www.youtube.com/watch?v=0DeznFqrgAI).

![image](https://github.com/waqqasiq/N-Queen-problem-using-backtracking/blob/master/backtracking.png)
