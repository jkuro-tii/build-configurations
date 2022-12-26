
.PHONY: install default

default: memtest

install: memtest
	mkdir -p $(out)
	cp $< $(out)

memtest: memtest.c
