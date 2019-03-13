
vpath %.c src
vpath %.h include

CC = gcc
CFLAGS = -g -Og -std=c11 -Wall -Wextra -pedantic
CPPFLAGS = -I include

PROJECT = stdmake

all: $(PROJECT)

$(PROJECT): stdmake.o
	$(CC) $(CFLAGS) $(CPPFLAGS) -o $@ $^

stdmake.o: stdmake.c
	$(CC) $(CFLAGS) $(CPPFLAGS) -c -o $@ $^

.PHONY: clean
clean:
	rm -rf *.o $(PROJECT)

