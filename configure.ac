dnl Process this file with Autoconf to produce configure

AC_INIT(stow.in)

PACKAGE=stow
VERSION=1.4.0
AM_INIT_AUTOMAKE(stow, $VERSION)
AC_SUBST(PACKAGE)
AC_SUBST(VERSION)

AC_ARG_PROGRAM

AC_PROG_INSTALL

AC_PATH_PROGS(PERL, perl perl5, false)

if test "x$PERL" = xfalse
then
  echo 'WARNING: Perl not found; you must edit line 1 of `stow'"'"
fi

AC_OUTPUT(Makefile stow)