CC = gcc
CFLAGS = -Wall -Wextra -pedantic -std=c11 -g

TARGET = hello

$(TARGET): $(TARGET).c
	$(CC) $(CFLAGS) -o $(TARGET) $(TARGET).c

clean:
	rm -rf $(TARGET)
