dnl Process this file with autoconf to produce a configure script

AC_PREREQ(2.69)
AC_INIT([rpmatch], [1.0], [pullmoll@t-online.de])
AM_INIT_AUTOMAKE([1.15])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_HEADER(config.h)

AC_PROG_CC
AC_PROG_LIBTOOL
LT_INIT

AC_CHECK_HEADERS(stddef.h stdio.h string.h regex.h libintl.h locale.h)

AC_CONFIG_FILES([Makefile musl-rpmatch.pc])
AC_OUTPUT
