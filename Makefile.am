lib_LIBRARIES=libhello.a
libhello_adir=$(includedir)/libhello
libhello_a_HEADERS = hello.h
libhello_a_SOURCES = $(libhello_a_HEADERS) \
                     hello.c

noinst_PROGRAMS = testhello
testhello_SOURCES = testhello.c
testhello_LDADD = $(top_builddir)/libhello.a
TESTS = testhello


