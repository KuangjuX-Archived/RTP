SRC = abp.c
EXEC = abp
ALL = ${EXEC}

.PHONY: build run clean 

build:
	@gcc -o ${EXEC} ${SRC}

run:
	@make build && ./${EXEC}

clean:
	@rm -rf ${ALL}