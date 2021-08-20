CC = gcc
CFLAGS = -O2 -g -Wall -I.
CFLAGS += -fsanitize=thread
LDFLAGS = -lpthread -fsanitize=thread

all: list

.PHONY:clean
clean:
	rm -f list