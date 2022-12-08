ACLOCAL_AMFLAGS=-I m4
lib_LTLIBRARIES = libinterflop_checkfloatmax.la

libinterflop_checkfloatmax_la_SOURCES = interflop_checkfloatmax.cxx
libinterflop_checkfloatmax_la_CFLAGS = -fno-stack-protector
libinterflop_checkfloatmax_la_CXXFLAGS = -fno-stack-protector

if WALL_CFLAGS
libinterflop_checkfloatmax_la_CFLAGS += -Wall -Wextra -Wno-varargs -Og -g
endif
if LINK_INTERFLOP_STDLIB
libinterflop_checkfloatmax_la_LIBADD = @INTERFLOP_STDLIB_PATH@/lib/libinterflop_stdlib.la
endif
libinterflop_checkfloatmax_la_includedir =$(includedir)/
include_HEADERS = interflop_checkfloatmax.h