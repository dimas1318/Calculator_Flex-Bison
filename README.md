# Compiler for Eiffel
Use: Flex and Bison

## Run the following commands in the terminal:
1. bison -y -d calculator.y&nbsp;&nbsp;//generate y.tab.c <br />
2. flex calculator.l&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//generate lex.yy.c <br />
3. gcc y.tab.c lex.yy.c&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;//generate a.out <br />
4. ./a.out <br />
