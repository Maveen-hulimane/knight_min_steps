# knight_min_steps

write a function called solution(src, dest) 
which takes in two parameters: the source square, on which you start, and the destination square, 
which is where you need to land to solve the puzzle.  The function should return an integer representing 
the smallest number of moves it will take for you to travel from the source square to the destination square 
using a chess knight's moves (that is, two squares in any direction immediately followed by one square perpendicular 
to that direction, or vice versa, in an "L" shape).  Both the source and destination squares will be an 
integer between 0 and 63, inclusive, and are numbered like the example chessboard below:

-------------------------------------------
| 0  | 1  | 2  | 3  | 4  | 5  | 6  | 7  |
------------------------------------------
| 8  | 9  | 10 | 11 | 12 | 13 | 14 | 15 |
------------------------------------------
| 16 | 17 | 18 | 19 | 20 | 21 | 22 | 23 |
------------------------------------------
| 24 | 25 | 26 | 27 | 28 | 29 | 30 | 31 |
------------------------------------------
| 32 | 33 | 34 | 35 | 36 | 37 | 38 | 39 |
------------------------------------------
| 40 | 41 | 42 | 43 | 44 | 45 | 46 | 47 |
-----------------------------------------
| 48 | 49 | 50 | 51 | 52 | 53 | 54 | 55 |
-----------------------------------------
| 56 | 57 | 58 | 59 | 60 | 61 | 62 | 63 |
-------------------------------------------


Test case:

    1.  start:0
        destination:1
            output:3
    2.  start:54
        destination:63
            output:4
    3.  start:10
        destination:19
            output:2
    4.  start:0
        destination:44
            output:3
    5.  start:44
        destination:44
            output:0
