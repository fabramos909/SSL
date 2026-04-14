# Variables para el compilador y los flags
CC = gcc
CFLAGS = -std=c2x

# Regla principal: compila el ejecutable
hello: hello.c
	$(CC) $(CFLAGS) hello.c -o hello

# Regla para limpiar los archivos generados
clean:
	del /f /q hello.exe output.txt