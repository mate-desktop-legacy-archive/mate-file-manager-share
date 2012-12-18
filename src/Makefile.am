libcaja_share_la_CFLAGS =				\
	-Wall						\
	-DG_LOG_DOMAIN=\"Caja-Share\"		\
	-DINTERFACES_DIR=\"$(interfacesdir)\"		\
	-DDATADIR=\"$(datadir)\"			\
	-I$(top_srcdir)					\
	-I$(top_builddir)				\
	$(WARN_CFLAGS)                                  \
	$(DISABLE_DEPRECATED_CFLAGS)			\
	$(CAJA_CFLAGS)				\
	$(GLIB_CFLAGS)

caja_extension_LTLIBRARIES=libcaja-share.la

libcaja_share_la_SOURCES =  \
	mate-file-manager-share.c        \
	mate-file-manager-share.h	\
	shares.c		\
	shares.h

libcaja_share_la_LDFLAGS = -module -avoid-version
libcaja_share_la_LIBADD  = $(GLIB_LIBS) $(CAJA_LIBS)
