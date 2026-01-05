build:
	nasm -f elf64 -o source.o source.asm

link:
	ld -o bin source.o

clean:
	rm -f source.o bin

run:
	./bin