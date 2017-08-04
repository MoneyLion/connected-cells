# connected-cells
A Typescript exercise in search algorithm

Consider a matrix with n rows and m columns, where each cell contains either a 0 or a 1 and any cell containing a 1 is called a filled cell. Two cells are said to be connected if they are adjacent to each other horizontally, vertically, or diagonally; in other words, cell [ j ][ k ] is connected to cells [ j - 1 ][ k - 1 ], [ j - 1 ][ k ], [ j - 1 ][ k + 1 ], [ j ][ k - 1], [ j ][ k + 1 ], [ j + 1][k - 1 ], [ j + 1 ][ k ], and [ j + 1 ][ k + 1 ], provided that the location exists in the matrix for that [ j ][ k ].

If one or more filled cells are also connected, they form a region. Note that each cell in a region is connected to at least one other cell in the region but is not necessarily directly connected to all the other cells in the region.

## Task 
Given an n * m matrix, find and print the number of cells in the largest region in the matrix. Note that there may be more than one region in the matrix.

## Requirement
You *MUST* use Typescript to complete this exercise.

## Test Cases

    n = 4, m = 4, matrix =
    1 1 0 0
	  0 1 1 0
	  0 0 1 0
	  1 0 0 0
    (Answer: 5)

    n = 5, m = 5, matrix =
    1 1 0 0 0
    0 1 1 0 0
    0 0 1 0 1
    1 0 0 0 1
    0 1 0 1 1
    (Answer: 5)

