all: jobshop

jobshop: jobshop.o simlib.o
	gcc -o jobshop jobshop.o simlib.o -lm
	./jobshop

clean:
	rm jobshop.o
	rm simlib.o
	rm jobshop
	rm res/jobshop.out
	rm res/log.txt

jobshop.o: jobshop.c
	gcc -c jobshop.c -o jobshop.o -I.

simlib.o: simlib.c
	gcc -c simlib.c -o simlib.o -I.