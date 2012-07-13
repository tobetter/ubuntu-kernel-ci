all: heroh_world

install: all
	env | sort
	install -d $(DESTDIR)/usr/bin
	install heroh_world $(DESTDIR)/usr/bin

clean:
	rm -f heroh_world
