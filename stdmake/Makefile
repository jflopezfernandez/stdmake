
vpath %.c src
vpath %.h include

PROJECT = stdmake

all: $(PROJECT)

$(PROJECT): stdmake.o

stdmake.o: stdmake.c

.PHONY: clean
clean:
	rm -rf *.o $(PROJECT)

