lex lex_spec.l
yacc -d yacc_spec.y
gcc lex.yy.c y.tab.c -ly -ll
./a.out < ex.java
