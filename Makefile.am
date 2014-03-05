AM_CFLAGS  = -Wall

lib_LTLIBRARIES = libedf.la

libedf_la_SOURCES = \
	edflib.c

indent: *.c *.h
	indent -linux $^
	rm $(foreach input,$^,$(input)~)
