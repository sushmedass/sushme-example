#                                               -*- Autoconf -*-
# Process this file with autoconf to produce a configure script.

#AC_PREREQ(2.60)
AC_INIT(test, 1.0)
AC_CONFIG_SRCDIR([sushmeExample.c])
AC_CONFIG_HEADER([config.h])
AM_INIT_AUTOMAKE(sushmeExample, main)

# Checks for programs.
AC_PROG_CC
AC_PROG_INSTALL
AC_PROG_MAKE_SET

# Checks for libraries.
AM_PROG_LIBTOOL

# Set shared libraries
AC_DISABLE_STATIC
AC_ENABLE_SHARED

#AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_FILES([Makefile])
AC_OUTPUT
