

sbin_PROGRAMS			+= syslog-ng-ctl/syslog-ng-ctl

syslog_ng_ctl_syslog_ng_ctl_SOURCES		= 	\
	syslog-ng-ctl/syslog-ng-ctl.c			\
	syslog-ng-ctl/control-client.h			\
	syslog-ng-ctl/control-client.c

EXTRA_DIST					+=	\
	syslog-ng-ctl/control-client-unix.c

syslog_ng_ctl_syslog_ng_ctl_LDADD		= lib/libsyslog-ng.la $(CRYPTO_LIBS) @BASE_LIBS@ @GLIB_LIBS@ @RESOLV_LIBS@

