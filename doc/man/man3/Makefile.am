man3_MANS      = $(srcdir)/libnet.3           \
                 $(srcdir)/libnet-functions.3 \
                 $(srcdir)/libnet-macros.3
DISTCLEANFILES = libnet.3 libnet-functions.3 libnet-macros.3
EXTRA_DIST     = $(man3_MANS)

if ENABLE_MAN
$(man3_MANS): doc

doc:
	$(MAKE) -C @top_builddir@ $@
endif
