CFLAGS = -Wall -g -DDEBUG
OBJECTS = ex1.c ex3.c ex8.c
CC = gcc

all:ex1.c ex3.c ex8.c ex20.c
	gcc $(CFLAGS) $^ -o $@

pre:ex20.c
	gcc -E $^ -o ex20.i


clean:
	rm -f ex1 ex3 ex8 ex20