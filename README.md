# Reverse-Polish-Notation-Calulator-Using-C

Reverse Polish notation (RPN), also known as Polish postfix notation or simply postfix notation, is a mathematical notation in which operators follow their operands, in contrast to Polish notation (PN), in which operators precede their operands.It does not need any parentheses as long as each operator has a fixed number of operands. 

  Infix notation ------> Reverse Polish Notation
  
( ( 1 + 3 ) / 4 ) ^  5	     ------->                  1 3 + 4 / 5 ^                                                                                                                                                             
( 1 + 2 ) * ( 3 / 4 ) ^ ( a + b )	 -------->         1 2 + 3 4 / a b + ^ *


The project was opened in VIM, edited, compiled, and ran/executed directly from Vim’s editor command line.

Installation Process:

1. First using the Shell Command Line in Terminal, tunnel to the project folder via “cd” (change directory) a command similar to

cd autodiction/vi-workspace/trial_menu

2. Using Vim Editor :

write command “vim filename.c or vi filename.cpp”.
Enter “I” , to activate insert mode in vi editor .
Write your code
Enter “Esc”
Enter “:”
write “wq” ,Enter.

3. Using Compiler :

for c code write “gcc - o filename filename.c” ,Enter
for cpp code write “g++ - o filename filename.cpp” , Enter
After compiling a runnable file will be created .

4. Run :

write “./filename” , Enter .
