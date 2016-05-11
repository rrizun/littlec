AC_INIT(main, 0.1)
AC_CONFIG_AUX_DIR([.])
AM_INIT_AUTOMAKE([foreign subdir-objects -Wall -Werror -Wno-portability])

AC_PROG_CC
AM_PROG_CC_C_O
AC_PROG_CXX
AC_PROG_RANLIB
#AC_PROG_LIBTOOL

AC_CONFIG_FILES([Makefile])

AC_CHECK_LIB([dl], [main])
AC_CHECK_LIB([rt], [main])
AC_CHECK_LIB([pthread], [main])

AC_OUTPUT