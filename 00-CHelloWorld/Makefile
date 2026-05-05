CC      = clang
CFLAGS  = -std=c23 -Wall -Wextra

hello: hello.c
	$(CC) $(CFLAGS) -o hello hello.c

run: hello
	./hello > output.txt

clean:
	rm -f hello output.txt

.PHONY: run clean