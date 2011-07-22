bin_SCRIPTS = mal2dot

xsldir = $(datadir)/mal2dot
xsl_DATA = mal2dot.xsl

EXTRA_DIST =			\
	ChangeLog		\
	$(xsl_DATA)		\
	mal2dot.xsl.in

ChangeLog:
	@if test -f $(top_srcdir)/.git/HEAD; then \
	  git log --stat > $@; \
	fi

dist: ChangeLog
.PHONY: ChangeLog
