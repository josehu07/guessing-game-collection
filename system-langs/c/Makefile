CC=gcc
CFLAGS=-std=c89 -O2

all: game
	
game: main.c guessing_game.c
	${CC} ${CFLAGS} $^ -o $@

.PHONY: clean
clean:
	rm -f game
