hello: hello.c
	gcc -std=c23 hello.c -o hello

run: hello
	.\hello.exe

output: hello
	.\hello.exe > output.txt

clean:
	rm -f hello.exe hello output.txt