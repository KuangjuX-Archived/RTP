SRC 			:= abp.c
EXEC 			:= abp
CC 				:= gcc
CFLAGS 			:= -std=c11
ALL 			:= $(EXEC)

.PHONY: build run clean 

build:
	@$(CC) -o $(EXEC) $(SRC) $(CFLAGS)

run:
	@make build && ./$(EXEC)

clean:
	@rm -rf $(ALL)