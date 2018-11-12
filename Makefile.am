# $Id$

ACLOCAL_AMFLAGS	= -I m4

MAINTAINERCLEANFILES = \
	config.log config.status \
	$(srcdir)/Makefile.in \
	$(srcdir)/config.h.in $(srcdir)/config.h.in~ \
	$(srcdir)/configure \
	$(srcdir)/install-sh $(srcdir)/ltmain.sh $(srcdir)/missing \
	$(srcdir)/depcomp $(srcdir)/aclocal.m4 $(srcdir)/compile \
	$(srcdir)/config.guess $(srcdir)/config.sub

include_HEADERS = evldns.h

bin_PROGRAMS	= fixed

fixed_SOURCES	= fixed.c evldns.c plugin.c function.c network.c
fixed_LDFLAGS	= -rdynamic -levent -lldns
