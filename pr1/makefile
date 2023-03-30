#makefile for hello.asm
hello: hello.o
	gcc  -no-pie -o hello hello.o
hello.o: hello.asm
	nasm -f elf64 -g -F dwarf hello.asm -l hello.lst