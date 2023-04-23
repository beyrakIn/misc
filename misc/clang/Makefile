CC=clang
FN=main.c

edit:
	vim $(FN)

run: 
	$(CC) $(FN) -o main
	./main

run32:
	$(CC) $(FN) -m32 -o main

build:
	$(CC) $(FN) -o main

build32:
	$(CC) $(FN) -m32 -o main

asm:
	$(CC) -S $(FN) -o asm.s

asm32:
	$(CC) -S -m32 $(FN) asm.s

clean:
	rm main *.s 
