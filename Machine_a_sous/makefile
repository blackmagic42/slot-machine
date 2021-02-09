EXEC=machine
CFLAGS=-lm -Wall
SRC=$(wildcard *.c)

all:COMPILE RUN
COMPILE: $(SRC)
	gcc $^ -o $(EXEC) $(CFLAGS)
RUN:COMPILE
	./$(EXEC)
