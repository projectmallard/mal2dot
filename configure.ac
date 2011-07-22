AC_INIT([mal2dot], [0.1.1], [])
AM_INIT_AUTOMAKE([1.9 no-dist-gzip dist-bzip2])

AC_CONFIG_MACRO_DIR([m4])

PKG_CHECK_MODULES(MALLARD_SITE_TOOL,
[
	yelp-xsl   >= 0.99.1
])

MAL_LINK="`$PKG_CONFIG --variable=xsltdir yelp-xsl`/mallard/common/mal-link.xsl"
AC_SUBST(MAL_LINK)

AC_CONFIG_FILES([
Makefile
mal2dot
mal2dot.xsl
])

AC_OUTPUT
