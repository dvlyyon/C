# The location of the expat directory

LIBS= -lgvc -lcgraph


OPT = -O

CFLAGS = $(OPT) 

help:
	@echo
	@echo "*********************************************************"
	@echo "** Provide as an argument the executable that you"
	@echo "** want built. The choices are:"
	@echo "**	simple"

simple: simple.o 
	$(CC) -o simple simple.o $(LIBS)
