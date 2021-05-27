CC			:= gcc
CFLAGS		:= -std=c11

.PHONY: build run clean 

build:
	@$(CC) -o gbn gbn.c $(CFLAGS)

run: build
	@./gbn

clean:
	@rm -rf gbn