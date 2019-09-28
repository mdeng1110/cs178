#!/bin/bash

compileServer:
	gcc ServerCountThrees.c readInt32BitLE.c -o ServerCountThrees
runServer:
	./ServerCountThrees threesData.bin
test:
	mkdir -p ../build/ \
	&& cp ../data/threesData.bin ../build/ \
	&& cp ServerCountThrees ../build/ \
	&& ../build/ServerCountThrees threesData.bin 
