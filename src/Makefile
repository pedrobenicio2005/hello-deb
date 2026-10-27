all: hello

hello: hello.c
	gcc -o hello hello.c

install:
	mkdir -p $(DESTDIR)/usr/bin
	install -m 755 hello $(DESTDIR)/usr/bin

clean:
	rm -f hello
