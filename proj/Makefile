
OBJ=fso-sh.o fs.o disk.o bitmap.o
HDR=fs.h disk.h bitmap.h

CFLAGS=-Wall -g 
# add -fsanitize=address to check memory errors in runtime 

all: fso-sh


fso-sh: $(OBJ) $(HDR)
	cc $(CFLAGS)  $(OBJ) -o fso-sh

clean:
	rm -f fso-sh $(OBJ) *~
