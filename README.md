# SNESmapFix
A simple C program for eliminating unnecessary values in map files produced by SuperFamiconv (v0.3.1)

Output file contains C array of hexadecimal indexes (map) of tiles used for drawing backgrounds and sprites on SNES.

The following values should be known before the start of main program:
  - INPUT_SIZE - size of input array
  - OUTPUT_SIZE - adjustable (or could be left as is)
  - GARBAGE(x) - garbage to be eliminated 
  
Optional:
  - FORMAT_OUTPUT - format output file in a specific number of columns

This project is made in Code::Blocks (v16.01)
