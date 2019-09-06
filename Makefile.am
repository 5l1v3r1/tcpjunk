## Process this file with automake to produce Makefile.in
## Created by Anjuta

SUBDIRS = src 

tcpjunkdocdir = ${prefix}/doc/tcpjunk
tcpjunkdoc_DATA = \
	README\
	COPYING\
	AUTHORS\
	ChangeLog\
	INSTALL\
	NEWS


EXTRA_DIST = $(tcpjunkdoc_DATA) \
	$(manpage_DATA)\
	$(desktop_DATA)\
	$(icon_DATA)

manpage_DATA = \
	tcpjunk.1

manpagedir = \
	/usr/man/man1

desktop_DATA = \
	tcpjunk.desktop

desktopdir = \
	/usr/share/applications

icon_DATA = \
	tcpjunk.png

icondir = \
	/usr/share/pixmaps

# Remove doc directory on uninstall
uninstall-local:
	-rm -r $(tcpjunkdocdir)
