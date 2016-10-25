## Compiling the user-level swifi controller
## You may need to adjust your include path to include <linux/swifi-user.h>
##  this means move swifi.h swifi-user.h to /usr/include/linux

CC := gcc
LD := gcc

PROG := swifi

all: $(PROG)

$(PROG): swifi.c

clean:
	rm -f $(PROG)
