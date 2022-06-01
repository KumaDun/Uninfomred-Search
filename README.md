N-Queen

In this section, you will develop a solver for the n-queens problem, wherein n
queens are to be placed on an n × n chessboard so that no pair of queens can
attack each other. Recall that in chess, a queen can attack any piece that lies in
the same row, column, or diagonal as itself.

a sensible
representation for a board configuration is a list of numbers between 0 and
n−1, where the ith number designates the column of the queen in row i for
0 < i ≤ n. A complete configuration is then specified by a list containing
n numbers, and a partial configuration is specified by a list containing
fewer than n numbers. 
