AC_INIT([yt-unblk], [1.0], [yt-unblk@localdesk.top])
AM_INIT_AUTOMAKE([-Wall -Werror foreign])
#AC_SEARCH_LIBS([mnl_socket_open], [libmnl], [], [
#  AC_MSG_ERROR([unable to find libmnl])
#])
AC_PROG_CC
#AC_CONFIG_HEADERS([])
PKG_CHECK_MODULES([MNL], [libmnl >= 1])
PKG_CHECK_MODULES([NFL], [libnfnetlink])
PKG_CHECK_MODULES([NFQ], [libnetfilter_queue])
AC_CONFIG_FILES([
  Makefile
])
AC_OUTPUT

