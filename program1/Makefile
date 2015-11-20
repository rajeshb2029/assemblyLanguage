ASMFLAGS = -f elf32
CFLAGS = -m32
TARGET = first

all:
	nasm $(ASMFLAGS) $(TARGET).asm
	gcc $(CFLAGS) -o $(TARGET) $(TARGET).o driver.c asm_io.o

clean:
	rm $(TARGET).o
