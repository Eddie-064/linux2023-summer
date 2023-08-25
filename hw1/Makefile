CFLAGS := -Wall
LDFLAGS := -lpthread

.PHONY: all
all:
	$(CC) -o s-tree q1.c
	$(CC) $(CFLAGS) -o qsort qsort-mt.c $(LDFLAGS)

.PHONY: clean
clean:
	rm ./s-tree ./qsort
