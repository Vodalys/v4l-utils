noinst_LTLIBRARIES = libv4l2subdev.la

libv4l2subdev_la_SOURCES = libv4l2subdev.c
libv4l2subdev_la_LIBADD = ../../lib/libmediactl/libmediactl.la
libv4l2subdev_la_CFLAGS = -static
libv4l2subdev_la_LDFLAGS = -static

noinst_HEADERS = v4l2subdev.h

bin_PROGRAMS = media-ctl
media_ctl_SOURCES = media-ctl.c options.c options.h
media_ctl_LDADD = ../../lib/libmediactl/libmediactl.la libv4l2subdev.la
