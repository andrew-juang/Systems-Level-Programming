all: main.o
	gcc -o program main.o

main.o: main.c
	gcc -c main.c

run:
	./program

clean:
	rm *.o
	rm program
	rm *.data

comprun: all
	./program
