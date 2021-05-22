SRC = abp.c
EXEC = abp
CC = gcc
CC_OPTIONS = -std=c11
ALL = ${EXEC}

.PHONY: build run clean 

build:
	@$(CC) -o $(EXEC) $(SRC) $(CC_OPTIONS)

run:
	@make build && ./$(EXEC)

clean:
	@rm -rf ${ALL}