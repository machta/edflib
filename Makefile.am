AM_CFLAGS  = -Wall

lib_LTLIBRARIES = libedflib.la

libedflib_la_SOURCES = edflib.c

include_HEADERS = edflib.h

indent: *.c *.h
	indent -linux $^
	rm $(foreach input,$^,$(input)~)
