TARGET = networktablet
PREFIX = /usr/local
BINDIR = $(PREFIX)/bin
export CC=c99
networktablet : networktablet.c protocol.h -lX11 -lXrandr 

clean :
	rm -f networktablet

install :
	install -D networktablet $(DESTDIR)$(BINDIR)/networktablet
