CC = g++
CCFLAGS = -Wall -lm -O2 -std=c++11

base: base.cpp
	${CC} ${CCFLAGS} $^ -o $@

test: base
	./base < data.in

output: base
	./base < data.in > data.out
