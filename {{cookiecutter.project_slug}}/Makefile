# Project Makefile.
# The results and figures should be reproducible from the functions/code in src,
# the scripts in the project main directory, and the data in 
# data/external and/or data/raw.
####################################################################
# I am a comment, and I want to say that the variable CC will be
# the compiler to use.
SH=/bin/sh
# Hey!, I am comment number 2. I want to say that CFLAGS will be the
# options I'll pass to the compiler.
CFLAGS=-c -Wall

all: hello_world.txt

hello_world.txt: hello_world.sh
	$(SH) hello_world.sh

clean:
	rm hello_world.txt

