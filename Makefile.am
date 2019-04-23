AM_CPPFLAGS=${GLIB_CFLAGS} ${PBC_CFLAGS} ${GMP_CFLAGS}
AM_LDFLAGS=${GLIB_LDFLAGS} ${PBC_LDFLAGS} ${GMP_LDFLAGS}

lib_LTLIBRARIES = libbswabe.la

libbswabe_la_SOURCES = core.c misc.c bswabe.h private.h

include_HEADERS = bswabe.h

dist_noinst_SCRIPTS = autogen.sh
