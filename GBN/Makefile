SRC = gbn.c
EXEC = gbn
ALL = ${EXEC}

.PHONY: build run clean 

build:
	@gcc -o ${EXEC} ${SRC}

run:
	@make build && ./${EXEC}

clean:
	@rm -rf ${ALL}