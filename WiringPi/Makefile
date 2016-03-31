all: clean build run
	clean build run

build: 
	gcc -Wall -o main.o main.c -lwiringPi

run: 	
	./main
		 
clean:
	-rm *.o
	
