# N-Queens!
The n-queens puzzle is the problem of placing n chess queens on an n×n chessboard so that no two queens threaten each other; thus, a solution requires that no two queens share the same row, column, or diagonal. Solutions exist for all natural numbers n with the exception of `n=2` and `n=3`.

<p align="center">
  <img width="300" src="https://upload.wikimedia.org/wikipedia/commons/1/1f/Eight-queens-animation.gif"></br>
  <i>A sample iterations for finding a correct formation of 8 queens.</i>
</p>

## Counting Solutions
The following tables give the number of solutions for placing n queens on an n × n board, both fundamental (sequence [A002562](https://oeis.org/A002562) in the [OEIS](https://en.wikipedia.org/wiki/On-Line_Encyclopedia_of_Integer_Sequences)) and all (sequence [A000170](https://oeis.org/A000170) in the [OEIS](https://en.wikipedia.org/wiki/On-Line_Encyclopedia_of_Integer_Sequences)).

| `n` | `fundamental` | `all` |
| -: | -----------: | ---: |
| 1 | 1 | 1 |
| 2 | 0 | 0 |
| 3 | 0 | 0 |
| 4 | 1 | 2 |
| 5 | 2 | 10 |
| 6 | 1 | 4 |
| 7 | 6 | 40 |
| 8 | 12 | 92 |
| 9 | 46 | 352 |
| 10 | 92 | 724 |
| 11 | 341 | 2,680 |
| 12 | 1,787 | 14,200 |
| 13 | 9,233 | 73,712 |
| 14 | 45,752 | 365,596 |
| 15 | 285,053 | 2,279,184 |
| 16 | 1,846,955 | 14,772,512 |
| 17 | 11,977,939 | 95,815,104 |
| 18 | 83,263,591 | 666,090,624 |
| 19 | 621,012,754 | 4,968,057,848 |
| 20 | 4,878,666,808 | 39,029,188,884 |
| 21 | 39,333,324,973 | 314,666,222,712 |
| 22 | 336,376,244,042 | 2,691,008,701,644 |
| 23 | 3,029,242,658,210 | 24,233,937,684,440 |
| 24 | 28,439,272,956,934 | 227,514,171,973,736 |
| 25 | 275,986,683,743,434 | 2,207,893,435,808,352 |
| 26 | 2,789,712,466,510,289 | 22,317,699,616,364,044 |
| 27 | 29,363,495,934,315,694 | 234,907,967,154,122,528 |

The six queens puzzle has fewer solutions than the five queens puzzle.
There is no known formula for the exact number of solutions, or even for its asymptotic behaviour. The [27×27](https://github.com/preusser/q27) board is the highest-order board that has been completely enumerated.
