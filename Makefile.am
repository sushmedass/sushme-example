AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic -O2
include_HEADERS = test.h

lib_LTLIBRARIES = libtest.la
libbbexample_la_SOURCES  = test.c
libbbexample_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = sushme-example
bbexample_SOURCES = sushme-example.c
bbexample_LDADD = libtest.la
