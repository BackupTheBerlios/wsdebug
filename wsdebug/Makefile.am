# Makefile.am
# Used by automake and configure to create Makefile.
#
# Copyright(C) 2004 Stefan Siegl, Germany
# Written by Stefan Siegl <ssiegl@gmx.de>
#

bin_PROGRAMS=wsdebug wsi

noinst_LIBRARIES=libwsi.a
libwsi_a_SOURCES=fileio.c interprt.c storage.c fileio.h interprt.h storage.h

wsdebug_SOURCES=wsdebug.c debug.c debug.h
wsdebug_LDADD=libwsi.a

wsi_SOURCES=wsi.c
wsi_LDADD=libwsi.a

EXTRA_DIST=
