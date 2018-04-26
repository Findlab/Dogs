# Dogs
The Problem of Dogs from Code of Duty contest.

***Beware: Very performance unwise implementation using minimum remaining value to determine places for dogs.*** 

**Problem Definition:**

Places of trees that are previously defined by the input will be placed on a NxN grid which is defined by the input again. The algorithm should place dogs such a way that:

  - Only one dog can be placed next to a tree
  - Dogs can not be placed in adjacent square
  - Dogs can be placed up,down,left or right side of a tree. Diagonal placement will not be accepted.
  - For each row and column,there can only be specific number of dogs. These restrictions are given as input.

The algorithm should output given trees and places of dogs. Input and output must be:
- “O” for void square.
- “T” for square with a tree.
- “D” for square with a dog.

In the first line of input, N and number of tree will be given as input,respectively.
In the second line of input, N number will be given as restriction of columns,respectively. 
In the third line,N number will be given as restriction of rows,respectively.
Then, N number of line,which consists of N number for each, will be given as input to place trees.

**Constraints:**

- Maximum value of grid size NxN is  15x15 

**Sample Input:**

4 3

1 0 1 1

1 0 2 0

O T O O

T O O O

O O O O

O O O T

**Sample Output:**

O T D O

T O O O

D O O D

O O O T
