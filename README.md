Spiral-Number-Matrix-Pattern-Generator
This code generates an n×n matrix filled with numbers from 1 to n² in a
clockwise spiral order, starting from the top-left corner.
It asks you for an integer n.
It creates an n × n NumPy matrix filled with zeros.
It then fills this matrix with numbers from 1 to n*n in a spiral pattern:
o Left → Right across the top row
o Top → Bottom down the rightmost column
o Right → Left across the bottom row
o Bottom → Top up the leftmost column
o Then it moves inward and repeats until all cells are filled.
Finally, it prints the resulting matrix.
