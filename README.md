# justify.c
A command line tool to justify a text to a width of 60

## Credit
The code for this tool comes from [C Programming A Modern Approch by K.N. King](http://knking.com/books/c2/index.html).

## Compiling
```
gcc -o justify justify.c word.c line.c
```
## Usage
```
❯ justify < lorem-ipsum.txt
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed
do eiusmod tempor  incididunt  ut  labore  et  dolore  magna
aliqua. Ut enim ad minim veniam, quis  nostrud  exercitation
ullamco laboris nisi ut aliquip  ex  ea  commodo  consequat.
Duis aute irure dolor in reprehenderit  in  voluptate  velit
esse cillum dolore eu fugiat nulla pariatur. Excepteur  sint
occaecat cupidatat non proident, sunt in culpa  qui  officia
deserunt mollit anim id est laborum.
```
## Reference
See line.h and word.h for a description of the functions in the corresponding source files line.c and word.c.
See justify.c for the main() function that runs the program.
The .txt files contain sample texts for you to use with the program.
