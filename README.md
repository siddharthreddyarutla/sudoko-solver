# sudoko-solver
Given a partially filled 9×9 2D array ‘grid[9][9]’, the goal is to assign digits (from 1 to 9) to the empty cells so that every row, column, and subgrid of size 3×3 contains exactly one instance of the digits from 1 to 9. 
 # input grid
 
 grid = [[2, 5, 0, 0, 3, 0, 9, 0, 1], <br>
        [0, 1, 0, 0, 0, 4, 0, 0, 0], <br>
    [4, 0, 7, 0, 0, 0, 2, 0, 8],<br>
    [0, 0, 5, 2, 0, 0, 0, 0, 0],<br>
    [0, 0, 0, 0, 9, 8, 1, 0, 0],<br>
    [0, 4, 0, 0, 0, 3, 0, 0, 0],<br>
    [0, 0, 0, 3, 6, 0, 0, 7, 2],<br>
    [0, 7, 0, 0, 0, 0, 0, 0, 3],<br>
    [9, 0, 3, 0, 0, 0, 6, 0, 4]]<br>

# output:

2 | 5 | 8 | 7 | 3 | 6 |9 | 4 | 1 |<br>
6 1 9 8 2 4 3 5 7 <br>
4 3 7 9 1 5 2 6 8 <br>
3 9 5 2 7 1 4 8 6 <br>
7 6 2 4 9 8 1 3 5 <br>
8 4 1 6 5 3 7 2 9 <br>
1 8 4 3 6 9 5 7 2 <br>
5 7 6 1 4 2 8 9 3 <br>
9 2 3 5 8 7 6 1 4 <br>
