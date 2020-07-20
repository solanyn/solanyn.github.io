---
layout: post
title:  "Sudoku and Algorithms"
date:   2020-07-20
excerpt: "Algorithms to solve Sudoku and Killer Sudoku puzzles"
project: true
tag:
- algorithms 
- sudoku 
comments: false 
---

## Sudoku and Algorithms

In the last semester, I took a class on algorithms. In the final assignment, we explored using algorithms to solve Sudoku puzzles of various difficulties and a variation of Sudoku known as Killer Sudoku.  

The assignment was very interesting and a lot of fun. We explored a simple backtracking method initially to solve the puzzles. This is akin to trying every number possible and going back if the solution is invalid until it finishes the puzzle, or no solution is possible. With this algorithm, it was observed that the solving times scaled with the puzzle difficulty classification since it would have more possibilities to try to attempt and backtrack to find the optimal solution.  

The next algorithm was much more interesting. We explored Donald Knuth's Dancing Links algorithm which uses a large matrix which represents every possibility of a Sudoku grid and attempts to find a solution using process of eliminating the invalid possibilities. It's rather complex to explain how the matrix is formed, but the searching itself is very fascinating. In essence, the search is still backtracking but the problem is transformed to a different form for more efficient search. Using this data structure reduces the search time significantly.  

Then we come to the Killer Sudoku variation. This puzzle has an additional restriction where cells of the Sudoku grid are grouped such that the cell value must sum up to a number specified by the group. These are known as cages and complicate the solving purpose. We first apply the backtracking algorithm but as we approach larger puzzles with larger cage sizes, the puzzles could take upwards of 10min to solve.  

Using Knuth's algorithm required additional modifications to solve the puzzles. Since there were new restrictions, I used a method to find all possible values that a cell could have based on the cage sum value. The algorithm would take additional time to find all the permutations that would sum up to cage sum value. Using the permutations, the matrix used in Knuth's algorithm can be modified such that values that weren't a possibility in the list of permutations could not be part of the solution. I ran short of time implementing this before submission, so the algorithm wasn't able to find the solution but on the puzzles where it find a solution, it ran in less than a second.  

Overall, it was a really interesting problem to think about. It's been fun to think really abstractly about the puzzle and how an algorithm can more efficiently search through possible values to find a solution to the problem.
