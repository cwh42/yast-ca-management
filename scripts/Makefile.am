#
# Makefile.am for installation/scripts
#
#
bindir = ${exec_prefix}/bin
sysconfdir = /etc

bin_SCRIPTS = generateCRL.pl exportCRL.pl

sysconf_DATA = generateCRL.conf

EXTRA_DIST =  $(bin_SCRIPTS) $(sysconf_DATA)

install-data-local:
	chmod 600 $(DESTDIR)/$(sysconfdir)/generateCRL.conf
