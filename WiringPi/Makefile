all: clean build run
	clean build run

build: 
	sudo gcc -Wall -o main.o main.c -lwiringPi

run: 	
	sudo ./main.o
		 
clean:
	sudo rm -rf *.o
	
