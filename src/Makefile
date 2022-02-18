all: main

main: main.o simlib.o
	gcc -o main main.o simlib.o -lm

clean:
	rm main.o
	rm simlib.o
	rm main

main.o: main.c
	gcc -c main.c -o main.o -I.

simlib.o: simlib.c
	gcc -c simlib.c -o simlib.o -I.