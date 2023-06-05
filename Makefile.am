AUTOMAKE_OPTIONS = foreign

CFLAGS = -Wall -pedantic -O2
include_HEADERS = test.h

lib_LTLIBRARIES = libtest.la
libbbexample_la_SOURCES  = test.c
libbbexample_la_LDFLAGS= -version-info 1:0:0

bin_PROGRAMS = sushme-example
sushme-example_SOURCES = sushme-example.c
sushme-example_LDADD = libtest.la
