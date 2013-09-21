## Introduction ##

Basic sudoku problem solver written in prolog.

## Example usage ##

| ?- ['sudoku.pl'].
compiling sudoku.pl for byte code...
sudoku.pl compiled, 51 lines read - 18639 bytes written, 13 ms

| ?- sudoku([_,3,_,4,_,6,9,_,7,2,_,6,8,5,_,4,3,1,4,1,7,2,_,3,_,5,8,_,6,9,_,3,4,7,8,2,1,_,3,_,7,_,5,4,_,7,4,_,5,2,9,_,6,3,6,5,2,7,8,_,3,_,4,9,_,1,3,_,5,2,7,6,3,7,_,9,_,2,_,1,5], Solution).

Solution = [8,3,5,4,1,6,9,2,7,2,9,6,8,5,7,4,3,1,4,1,7,2,9,3,6,5,8,5,6,9,1,3,4,7,8,2,1,2,3,6,7,8,5,4,9,7,4,8,5,2,9,1,6,3,6,5,2,7,8,1,3,9,4,9,8,1,3,4,5,2,7,6,3,7,4,9,6,2,8,1,5]

