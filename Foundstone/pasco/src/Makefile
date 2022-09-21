all: install

install:  pasco.c
	gcc -o pasco pasco.c -lm -lc;cp pasco ../bin

installwin:  pasco.c
	gcc -DCYGWIN -o pasco.exe pasco.c -lm -lc;cp pasco.exe ../bin

clean: 
	rm -f pasco.exe pasco
