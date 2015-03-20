if WITH_LIBV4L
lib_LTLIBRARIES = libmediactl.la
include_HEADERS = ../include/libmediactl.h
pkgconfig_DATA = libmediactl.pc
LIBMEDIACTL_VERSION = -version-info 0
else
noinst_LTLIBRARIES = libmediactl.la
endif

libmediactl_la_SOURCES = libmediactl.c
libmediactl_la_CPPFLAGS = $(CFLAG_VISIBILITY) $(ENFORCE_LIBV4L_STATIC)
libmediactl_la_LDFLAGS = $(LIBMEDIACTL_VERSION) -lpthread $(ENFORCE_LIBV4L_STATIC)
