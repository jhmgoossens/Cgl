# Copyright (C) 2006 International Business Machines and others.
# All Rights Reserved.
# This file is distributed under the Eclipse Public License.
#
# Author:  Andreas Waechter           IBM    2006-04-13

########################################################################
#                          libCglFlowCover                             #
########################################################################

# Name of the library compiled in this directory.  We don't want it to be
# installed since it will be collected into the libCgl library
noinst_LTLIBRARIES = libCglFlowCover.la

# List all source files for this library, including headers
libCglFlowCover_la_SOURCES = CglFlowCover.cpp CglFlowCover.hpp CglFlowCoverTest.cpp

# This is for libtool
AM_LDFLAGS = $(LT_LDFLAGS)

# Here list all include flags, relative to this "srcdir" directory.
AM_CPPFLAGS = $(CGLLIB_CFLAGS)

########################################################################
#                Headers that need to be installed                     #
########################################################################

# Here list all the header files that are required by a user of the library,
# and that therefore should be installed in $(includedir)/coin-or.
includecoindir = $(includedir)/coin-or
includecoin_HEADERS = CglFlowCover.hpp
