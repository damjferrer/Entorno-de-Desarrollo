CC=gcc
CGFLAGS=-Wall -g

calcula: calcula.c calc.o
	gcc -Wall -g calcula.c calc.o -o calcula

calc.o: calc.c calc.h

.PHONY: clean
clean:
	rm -rf *.o