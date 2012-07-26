CFLAGS = -I ..
CC=arm-linux-gcc

dump.cgi: dump.cgi.o
	$(CC) -o dump.cgi dump.cgi.o -L .. -lccgi

dump.cgi.o: dump.cgi.c
