all: menu.o min.o max.o diff.o sum.o
 gcc menu.o min.o max.o diff.o sum.o -o menu
    
menu.o: menu.c min.h max.h diff.h sum.h
 gcc -gnu=std99 -c menu.c

min.o: min.c
 gcc -gnu=std99 -c min.c 
    
max.o: max.c
 gcc -gnu=std99 -c max.c
    
diff.o: diff.c
 gcc -gnu=std99 -c diff.c
    
sum.o: sum.c
 gcc -gnu=std99 -c sum.c