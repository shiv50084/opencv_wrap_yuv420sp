# Makefile.in generated by automake 1.9.6 from Makefile.am.
# otherlibs/highgui/Makefile.  Generated from Makefile.in by configure.

# Copyright (C) 1994, 1995, 1996, 1997, 1998, 1999, 2000, 2001, 2002,
# 2003, 2004, 2005  Free Software Foundation, Inc.
# This Makefile.in is free software; the Free Software Foundation
# gives unlimited permission to copy and/or distribute it,
# with or without modifications, as long as this notice is preserved.

# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY, to the extent permitted by law; without
# even the implied warranty of MERCHANTABILITY or FITNESS FOR A
# PARTICULAR PURPOSE.




srcdir = .
top_srcdir = ../..

pkgdatadir = $(datadir)/opencv
pkglibdir = $(libdir)/opencv
pkgincludedir = $(includedir)/opencv
top_builddir = ../..
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
INSTALL = /usr/bin/install -c
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = x86_64-unknown-linux-gnu
host_triplet = arm-himix100-linux-gnu
target_triplet = arm-himix100-linux-gnu
subdir = otherlibs/highgui
DIST_COMMON = $(libhighguiinclude_HEADERS) $(noinst_HEADERS) \
	$(srcdir)/Makefile.am $(srcdir)/Makefile.in
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/autotools/aclocal/az_python.m4 \
	$(top_srcdir)/autotools/aclocal/pkg.m4 \
	$(top_srcdir)/autotools/aclocal/swig_complete.m4 \
	$(top_srcdir)/autotools/aclocal/version_at_least.m4 \
	$(top_srcdir)/configure.in
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
mkinstalldirs = $(SHELL) $(top_srcdir)/autotools/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/cvconfig.h
CONFIG_CLEAN_FILES =
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = `echo $$p | sed -e 's|^.*/||'`;
am__installdirs = "$(DESTDIR)$(libdir)" \
	"$(DESTDIR)$(libhighguiincludedir)"
libLTLIBRARIES_INSTALL = $(INSTALL)
LTLIBRARIES = $(lib_LTLIBRARIES) $(noinst_LTLIBRARIES)
lib_highgui_la_LIBADD =
am__lib_highgui_la_SOURCES_DIST = bitstrm.cpp grfmt_base.cpp \
	grfmt_bmp.cpp grfmt_jpeg.cpp grfmt_png.cpp grfmt_pxm.cpp \
	grfmt_jpeg2000.cpp grfmt_exr.cpp grfmt_sunras.cpp \
	grfmt_tiff.cpp image.cpp loadsave.cpp precomp.cpp utils.cpp \
	cvcap.cpp window.cpp cvcap_dc1394.cpp cvcap_v4l.cpp \
	cvcap_ffmpeg.cpp cvcap_qt.cpp cvcap_xine.cpp window_gtk.cpp \
	window_carbon.cpp
#am__objects_1 = cvcap_dc1394.lo
#am__objects_2 = cvcap_v4l.lo
#am__objects_3 = cvcap_ffmpeg.lo
#am__objects_4 = cvcap_qt.lo
#am__objects_5 = cvcap_xine.lo
#am__objects_6 = window_gtk.lo
#am__objects_7 = window_carbon.lo
am_lib_highgui_la_OBJECTS = bitstrm.lo grfmt_base.lo grfmt_bmp.lo \
	grfmt_jpeg.lo grfmt_png.lo grfmt_pxm.lo grfmt_jpeg2000.lo \
	grfmt_exr.lo grfmt_sunras.lo grfmt_tiff.lo image.lo \
	loadsave.lo precomp.lo utils.lo cvcap.lo window.lo \
	$(am__objects_1) $(am__objects_2) $(am__objects_3) \
	$(am__objects_4) $(am__objects_5) $(am__objects_6) \
	$(am__objects_7)
lib_highgui_la_OBJECTS = $(am_lib_highgui_la_OBJECTS)
libhighgui_la_DEPENDENCIES = lib_highgui.la \
	$(top_builddir)/cxcore/src/libcxcore.la \
	$(top_builddir)/cv/src/libcv.la 
am_libhighgui_la_OBJECTS = dummy.lo
libhighgui_la_OBJECTS = $(am_libhighgui_la_OBJECTS)
DEFAULT_INCLUDES = -I. -I$(srcdir) -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/autotools/depcomp
am__depfiles_maybe = depfiles
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
LTCOMPILE = $(LIBTOOL) --tag=CC --mode=compile $(CC) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CFLAGS) $(CFLAGS)
CCLD = $(CC)
LINK = $(LIBTOOL) --tag=CC --mode=link $(CCLD) $(AM_CFLAGS) $(CFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
CXXCOMPILE = $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
LTCXXCOMPILE = $(LIBTOOL) --tag=CXX --mode=compile $(CXX) $(DEFS) \
	$(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) \
	$(AM_CXXFLAGS) $(CXXFLAGS)
CXXLD = $(CXX)
CXXLINK = $(LIBTOOL) --tag=CXX --mode=link $(CXXLD) $(AM_CXXFLAGS) \
	$(CXXFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
SOURCES = $(lib_highgui_la_SOURCES) $(libhighgui_la_SOURCES)
DIST_SOURCES = $(am__lib_highgui_la_SOURCES_DIST) \
	$(libhighgui_la_SOURCES)
libhighguiincludeHEADERS_INSTALL = $(INSTALL_HEADER)
HEADERS = $(libhighguiinclude_HEADERS) $(noinst_HEADERS)
ETAGS = etags
CTAGS = ctags
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/zhouhua/HISI/opencv/opencv-1.0.0/autotools/missing --run aclocal-1.9
ALLOCA = 
AMDEP_FALSE = #
AMDEP_TRUE = 
AMTAR = ${SHELL} /home/zhouhua/HISI/opencv/opencv-1.0.0/autotools/missing --run tar
AR = arm-himix100-linux-ar
AS = as
AUTOCONF = ${SHELL} /home/zhouhua/HISI/opencv/opencv-1.0.0/autotools/missing --run autoconf
AUTOHEADER = ${SHELL} /home/zhouhua/HISI/opencv/opencv-1.0.0/autotools/missing --run autoheader
AUTOMAKE = ${SHELL} /home/zhouhua/HISI/opencv/opencv-1.0.0/autotools/missing --run automake-1.9
AWK = gawk
BUILD_APPS_FALSE = #
BUILD_APPS_TRUE = 
BUILD_CARBON_FALSE = 
BUILD_CARBON_TRUE = #
BUILD_DC1394_FALSE = 
BUILD_DC1394_TRUE = #
BUILD_FFMPEG_FALSE = 
BUILD_FFMPEG_TRUE = #
BUILD_GTK_FALSE = 
BUILD_GTK_TRUE = #
BUILD_PYTHON_WRAPPERS_FALSE = 
BUILD_PYTHON_WRAPPERS_TRUE = #
BUILD_QUICKTIME_FALSE = 
BUILD_QUICKTIME_TRUE = #
BUILD_V4L_FALSE = 
BUILD_V4L_TRUE = #
BUILD_XINE_FALSE = 
BUILD_XINE_TRUE = #
CARBON_CFLAGS = 
CARBON_LIBS = 
CC = arm-himix100-linux-gcc
CCDEPMODE = depmode=gcc3
CFLAGS = -mcpu=cortex-a7 -mfloat-abi=softfp -mfpu=neon-vfpv4 -fno-aggressive-loop-optimizations
CPP = arm-himix100-linux-gcc -E
CPPFLAGS = -DNDEBUG 
CXX = arm-himix100-linux-g++
CXXCPP = arm-himix100-linux-g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = -Wall -fno-rtti -pipe -O3 -fomit-frame-pointer -mcpu=cortex-a7 -mfloat-abi=softfp -mfpu=neon-vfpv4 -fno-aggressive-loop-optimizations
CYGPATH_W = echo
DEBUG = 
DEFS = -DHAVE_CONFIG_H
DEPDIR = .deps
DLLTOOL = dlltool
ECHO = echo
ECHO_C = 
ECHO_N = -n
ECHO_T = 
EGREP = grep -E
EXEEXT = 
F77 = 
FFLAGS = 
FFMPEGLIBS = 
GTHREAD_CFLAGS = 
GTHREAD_LIBS = 
GTK_CFLAGS = 
GTK_LIBS = 
IEEE1394LIBS = 
IMAGELIBS = 
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = ${SHELL} $(install_sh) -c -s
LDFLAGS = 
LIBOBJS = 
LIBS = -lpthread -ldl -lm 
LIBTOOL = $(SHELL) $(top_builddir)/libtool
LN_S = ln -s
LTLIBOBJS = 
LT_VERSION = 1:0:0
MAKEINFO = ${SHELL} /home/zhouhua/HISI/opencv/opencv-1.0.0/autotools/missing --run makeinfo
MMAJOR = 1
MMINOR = 0
MSUBMINOR = 0
OBJDUMP = objdump
OBJEXT = o
PACKAGE = opencv
PACKAGE_BUGREPORT = opencvlibrary-devel@lists.sourceforge.net
PACKAGE_NAME = opencv
PACKAGE_STRING = opencv 1.0.0
PACKAGE_TARNAME = opencv
PACKAGE_VERSION = 1.0.0
PATH_SEPARATOR = :
PKG_CONFIG = /usr/bin/pkg-config
PYTHON = /usr/bin/python
PYTHON_CSPEC = -fPIC -I/usr/include/python2.7
PYTHON_EXEC_PREFIX = ${exec_prefix}
PYTHON_LSPEC = -Wl,-Bsymbolic-functions -Wl,-z,relro -L/usr/lib/python2.7/config-x86_64-linux-gnu -lm -lpthread -ldl  -lutil -lpython2.7 -Xlinker -export-dynamic -Wl,-O1 -Wl,-Bsymbolic-functions
PYTHON_PLATFORM = linux2
PYTHON_PREFIX = ${prefix}
PYTHON_VERSION = 2.7
QUICKTIME_CFLAGS = 
QUICKTIME_LIBS = 
RANLIB = arm-himix100-linux-ranlib
SET_MAKE = 
SHELL = /bin/sh
STRIP = arm-himix100-linux-strip
SWIG = 
SWIG_PYTHON_LIBS = 
SWIG_PYTHON_OPT = 
SWIG_RUNTIME_LIBS_DIR = 
SWIG_VERSION = 
UPDATE_SWIG_WRAPPERS_FALSE = 
UPDATE_SWIG_WRAPPERS_TRUE = #
VERSION = 1.0.0
XINE_LIBS = 
ac_ct_AR = 
ac_ct_AS = 
ac_ct_CC = 
ac_ct_CXX = 
ac_ct_DLLTOOL = 
ac_ct_F77 = 
ac_ct_OBJDUMP = 
ac_ct_RANLIB = 
ac_ct_STRIP = 
am__fastdepCC_FALSE = #
am__fastdepCC_TRUE = 
am__fastdepCXX_FALSE = #
am__fastdepCXX_TRUE = 
am__include = include
am__leading_dot = .
am__quote = 
am__tar = ${AMTAR} chof - "$$tardir"
am__untar = ${AMTAR} xf -
bindir = ${exec_prefix}/bin
build = x86_64-unknown-linux-gnu
build_alias = 
build_cpu = x86_64
build_os = linux-gnu
build_vendor = unknown
datadir = ${prefix}/share
exec_prefix = ${prefix}
host = arm-himix100-linux-gnu
host_alias = arm-himix100-linux
host_cpu = arm
host_os = linux-gnu
host_vendor = himix100
includedir = ${prefix}/include
infodir = ${prefix}/info
install_sh = /home/zhouhua/HISI/opencv/opencv-1.0.0/autotools/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localstatedir = ${prefix}/var
mandir = ${prefix}/man
mkdir_p = mkdir -p --
oldincludedir = /usr/include
pkgpyexecdir = ${pyexecdir}/opencv
pkgpythondir = ${pythondir}/opencv
prefix = /home/zhouhua/HISI/opencv/install
program_transform_name = s,^,arm-himix100-linux-,
pyexecdir = ${exec_prefix}/lib/python2.7/site-packages
pythondir = ${prefix}/lib/python2.7/site-packages
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
sysconfdir = ${prefix}/etc
target = arm-himix100-linux-gnu
target_alias = arm-himix100-linux
target_cpu = arm
target_os = linux-gnu
target_vendor = himix100
EXTRA_DIST = highgui.dsp highgui.vcproj highgui.rc resource.h    \
    cvcap_cmu.cpp cvcap_tyzx.cpp cvcap_vfw.cpp cvcap_mil.cpp     \
    cvcap_qt.cpp cvcap_dc1394.cpp cvcap_ffmpeg.cpp               \
    cvcap_v4l.cpp cvcap_xine.cpp                                 \
    window_carbon.cpp window_gtk.cpp window_w32.cpp

INCLUDES = -I. -I$(top_srcdir)/cxcore/include \
    -I$(top_srcdir)/cv/include   \
     

noinst_HEADERS = \
    _highgui.h bitstrm.h grfmt_base.h grfmt_bmp.h \
    grfmt_jpeg.h grfmt_jpeg2000.h grfmt_exr.h \
    grfmt_pxm.h grfmt_png.h grfmt_sunras.h grfmt_tiff.h grfmts.h utils.h

noinst_LTLIBRARIES = lib_highgui.la
lib_LTLIBRARIES = libhighgui.la
TMP_DC1394 = 
#TMP_DC1394 = cvcap_dc1394.cpp
TMP_V4L = 
#TMP_V4L = cvcap_v4l.cpp
TMP_FFMPEG = 
#TMP_FFMPEG = cvcap_ffmpeg.cpp
TMP_XINE = 
#TMP_XINE = cvcap_xine.cpp
TMP_QT = 
#TMP_QT = cvcap_qt.cpp
TMP_CARBON = 
#TMP_CARBON = window_carbon.cpp
TMP_GTK = 
#TMP_GTK = window_gtk.cpp

# convenience library
lib_highgui_la_SOURCES = \
    bitstrm.cpp grfmt_base.cpp grfmt_bmp.cpp grfmt_jpeg.cpp      \
    grfmt_png.cpp grfmt_pxm.cpp grfmt_jpeg2000.cpp grfmt_exr.cpp \
    grfmt_sunras.cpp grfmt_tiff.cpp image.cpp loadsave.cpp       \
    precomp.cpp utils.cpp cvcap.cpp window.cpp                   \
    $(TMP_DC1394) $(TMP_V4L) $(TMP_FFMPEG) $(TMP_QT)             \
    $(TMP_XINE) $(TMP_GTK) $(TMP_CARBON)

lib_highgui_la_LDFLAGS = -no-undefined 

# real library
libhighguiincludedir = $(includedir)/opencv
libhighguiinclude_HEADERS = highgui.h
libhighgui_la_SOURCES = dummy.cpp
libhighgui_la_LDFLAGS = -no-undefined -version-info 1:0:0 
libhighgui_la_LIBADD = \
    lib_highgui.la \
    $(top_builddir)/cxcore/src/libcxcore.la \
    $(top_builddir)/cv/src/libcv.la         \
         \
       

all: all-am

.SUFFIXES:
.SUFFIXES: .c .cpp .lo .o .obj
$(srcdir)/Makefile.in:  $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh \
		&& exit 0; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --gnu  otherlibs/highgui/Makefile'; \
	cd $(top_srcdir) && \
	  $(AUTOMAKE) --gnu  otherlibs/highgui/Makefile
.PRECIOUS: Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe);; \
	esac;

$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh

$(top_srcdir)/configure:  $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4):  $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
install-libLTLIBRARIES: $(lib_LTLIBRARIES)
	@$(NORMAL_INSTALL)
	test -z "$(libdir)" || $(mkdir_p) "$(DESTDIR)$(libdir)"
	@list='$(lib_LTLIBRARIES)'; for p in $$list; do \
	  if test -f $$p; then \
	    f=$(am__strip_dir) \
	    echo " $(LIBTOOL) --mode=install $(libLTLIBRARIES_INSTALL) $(INSTALL_STRIP_FLAG) '$$p' '$(DESTDIR)$(libdir)/$$f'"; \
	    $(LIBTOOL) --mode=install $(libLTLIBRARIES_INSTALL) $(INSTALL_STRIP_FLAG) "$$p" "$(DESTDIR)$(libdir)/$$f"; \
	  else :; fi; \
	done

uninstall-libLTLIBRARIES:
	@$(NORMAL_UNINSTALL)
	@set -x; list='$(lib_LTLIBRARIES)'; for p in $$list; do \
	  p=$(am__strip_dir) \
	  echo " $(LIBTOOL) --mode=uninstall rm -f '$(DESTDIR)$(libdir)/$$p'"; \
	  $(LIBTOOL) --mode=uninstall rm -f "$(DESTDIR)$(libdir)/$$p"; \
	done

clean-libLTLIBRARIES:
	-test -z "$(lib_LTLIBRARIES)" || rm -f $(lib_LTLIBRARIES)
	@list='$(lib_LTLIBRARIES)'; for p in $$list; do \
	  dir="`echo $$p | sed -e 's|/[^/]*$$||'`"; \
	  test "$$dir" != "$$p" || dir=.; \
	  echo "rm -f \"$${dir}/so_locations\""; \
	  rm -f "$${dir}/so_locations"; \
	done

clean-noinstLTLIBRARIES:
	-test -z "$(noinst_LTLIBRARIES)" || rm -f $(noinst_LTLIBRARIES)
	@list='$(noinst_LTLIBRARIES)'; for p in $$list; do \
	  dir="`echo $$p | sed -e 's|/[^/]*$$||'`"; \
	  test "$$dir" != "$$p" || dir=.; \
	  echo "rm -f \"$${dir}/so_locations\""; \
	  rm -f "$${dir}/so_locations"; \
	done
lib_highgui.la: $(lib_highgui_la_OBJECTS) $(lib_highgui_la_DEPENDENCIES) 
	$(CXXLINK)  $(lib_highgui_la_LDFLAGS) $(lib_highgui_la_OBJECTS) $(lib_highgui_la_LIBADD) $(LIBS)
libhighgui.la: $(libhighgui_la_OBJECTS) $(libhighgui_la_DEPENDENCIES) 
	$(CXXLINK) -rpath $(libdir) $(libhighgui_la_LDFLAGS) $(libhighgui_la_OBJECTS) $(libhighgui_la_LIBADD) $(LIBS)

mostlyclean-compile:
	-rm -f *.$(OBJEXT)

distclean-compile:
	-rm -f *.tab.c

include ./$(DEPDIR)/bitstrm.Plo
include ./$(DEPDIR)/cvcap.Plo
include ./$(DEPDIR)/cvcap_dc1394.Plo
include ./$(DEPDIR)/cvcap_ffmpeg.Plo
include ./$(DEPDIR)/cvcap_qt.Plo
include ./$(DEPDIR)/cvcap_v4l.Plo
include ./$(DEPDIR)/cvcap_xine.Plo
include ./$(DEPDIR)/dummy.Plo
include ./$(DEPDIR)/grfmt_base.Plo
include ./$(DEPDIR)/grfmt_bmp.Plo
include ./$(DEPDIR)/grfmt_exr.Plo
include ./$(DEPDIR)/grfmt_jpeg.Plo
include ./$(DEPDIR)/grfmt_jpeg2000.Plo
include ./$(DEPDIR)/grfmt_png.Plo
include ./$(DEPDIR)/grfmt_pxm.Plo
include ./$(DEPDIR)/grfmt_sunras.Plo
include ./$(DEPDIR)/grfmt_tiff.Plo
include ./$(DEPDIR)/image.Plo
include ./$(DEPDIR)/loadsave.Plo
include ./$(DEPDIR)/precomp.Plo
include ./$(DEPDIR)/utils.Plo
include ./$(DEPDIR)/window.Plo
include ./$(DEPDIR)/window_carbon.Plo
include ./$(DEPDIR)/window_gtk.Plo

.c.o:
	if $(COMPILE) -MT $@ -MD -MP -MF "$(DEPDIR)/$*.Tpo" -c -o $@ $<; \
	then mv -f "$(DEPDIR)/$*.Tpo" "$(DEPDIR)/$*.Po"; else rm -f "$(DEPDIR)/$*.Tpo"; exit 1; fi
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c $<

.c.obj:
	if $(COMPILE) -MT $@ -MD -MP -MF "$(DEPDIR)/$*.Tpo" -c -o $@ `$(CYGPATH_W) '$<'`; \
	then mv -f "$(DEPDIR)/$*.Tpo" "$(DEPDIR)/$*.Po"; else rm -f "$(DEPDIR)/$*.Tpo"; exit 1; fi
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(COMPILE) -c `$(CYGPATH_W) '$<'`

.c.lo:
	if $(LTCOMPILE) -MT $@ -MD -MP -MF "$(DEPDIR)/$*.Tpo" -c -o $@ $<; \
	then mv -f "$(DEPDIR)/$*.Tpo" "$(DEPDIR)/$*.Plo"; else rm -f "$(DEPDIR)/$*.Tpo"; exit 1; fi
#	source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CCDEPMODE) $(depcomp) \
#	$(LTCOMPILE) -c -o $@ $<

.cpp.o:
	if $(CXXCOMPILE) -MT $@ -MD -MP -MF "$(DEPDIR)/$*.Tpo" -c -o $@ $<; \
	then mv -f "$(DEPDIR)/$*.Tpo" "$(DEPDIR)/$*.Po"; else rm -f "$(DEPDIR)/$*.Tpo"; exit 1; fi
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXXCOMPILE) -c -o $@ $<

.cpp.obj:
	if $(CXXCOMPILE) -MT $@ -MD -MP -MF "$(DEPDIR)/$*.Tpo" -c -o $@ `$(CYGPATH_W) '$<'`; \
	then mv -f "$(DEPDIR)/$*.Tpo" "$(DEPDIR)/$*.Po"; else rm -f "$(DEPDIR)/$*.Tpo"; exit 1; fi
#	source='$<' object='$@' libtool=no \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(CXXCOMPILE) -c -o $@ `$(CYGPATH_W) '$<'`

.cpp.lo:
	if $(LTCXXCOMPILE) -MT $@ -MD -MP -MF "$(DEPDIR)/$*.Tpo" -c -o $@ $<; \
	then mv -f "$(DEPDIR)/$*.Tpo" "$(DEPDIR)/$*.Plo"; else rm -f "$(DEPDIR)/$*.Tpo"; exit 1; fi
#	source='$<' object='$@' libtool=yes \
#	DEPDIR=$(DEPDIR) $(CXXDEPMODE) $(depcomp) \
#	$(LTCXXCOMPILE) -c -o $@ $<

mostlyclean-libtool:
	-rm -f *.lo

clean-libtool:
	-rm -rf .libs _libs

distclean-libtool:
	-rm -f libtool
uninstall-info-am:
install-libhighguiincludeHEADERS: $(libhighguiinclude_HEADERS)
	@$(NORMAL_INSTALL)
	test -z "$(libhighguiincludedir)" || $(mkdir_p) "$(DESTDIR)$(libhighguiincludedir)"
	@list='$(libhighguiinclude_HEADERS)'; for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  f=$(am__strip_dir) \
	  echo " $(libhighguiincludeHEADERS_INSTALL) '$$d$$p' '$(DESTDIR)$(libhighguiincludedir)/$$f'"; \
	  $(libhighguiincludeHEADERS_INSTALL) "$$d$$p" "$(DESTDIR)$(libhighguiincludedir)/$$f"; \
	done

uninstall-libhighguiincludeHEADERS:
	@$(NORMAL_UNINSTALL)
	@list='$(libhighguiinclude_HEADERS)'; for p in $$list; do \
	  f=$(am__strip_dir) \
	  echo " rm -f '$(DESTDIR)$(libhighguiincludedir)/$$f'"; \
	  rm -f "$(DESTDIR)$(libhighguiincludedir)/$$f"; \
	done

ID: $(HEADERS) $(SOURCES) $(LISP) $(TAGS_FILES)
	list='$(SOURCES) $(HEADERS) $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	mkid -fID $$unique
tags: TAGS

TAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	if test -z "$(ETAGS_ARGS)$$tags$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	    $$tags $$unique; \
	fi
ctags: CTAGS
CTAGS:  $(HEADERS) $(SOURCES)  $(TAGS_DEPENDENCIES) \
		$(TAGS_FILES) $(LISP)
	tags=; \
	here=`pwd`; \
	list='$(SOURCES) $(HEADERS)  $(LISP) $(TAGS_FILES)'; \
	unique=`for i in $$list; do \
	    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
	  done | \
	  $(AWK) '    { files[$$0] = 1; } \
	       END { for (i in files) print i; }'`; \
	test -z "$(CTAGS_ARGS)$$tags$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$tags $$unique

GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && cd $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) $$here

distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags

distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's|.|.|g'`; \
	list='$(DISTFILES)'; for file in $$list; do \
	  case $$file in \
	    $(srcdir)/*) file=`echo "$$file" | sed "s|^$$srcdirstrip/||"`;; \
	    $(top_srcdir)/*) file=`echo "$$file" | sed "s|^$$topsrcdirstrip/|$(top_builddir)/|"`;; \
	  esac; \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  dir=`echo "$$file" | sed -e 's,/[^/]*$$,,'`; \
	  if test "$$dir" != "$$file" && test "$$dir" != "."; then \
	    dir="/$$dir"; \
	    $(mkdir_p) "$(distdir)$$dir"; \
	  else \
	    dir=''; \
	  fi; \
	  if test -d $$d/$$file; then \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -pR $(srcdir)/$$file $(distdir)$$dir || exit 1; \
	    fi; \
	    cp -pR $$d/$$file $(distdir)$$dir || exit 1; \
	  else \
	    test -f $(distdir)/$$file \
	    || cp -p $$d/$$file $(distdir)/$$file \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(LTLIBRARIES) $(HEADERS)
installdirs:
	for dir in "$(DESTDIR)$(libdir)" "$(DESTDIR)$(libhighguiincludedir)"; do \
	  test -z "$$dir" || $(mkdir_p) "$$dir"; \
	done
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am

install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am

installcheck: installcheck-am
install-strip:
	$(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	  install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	  `test -z '$(STRIP)' || \
	    echo "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'"` install
mostlyclean-generic:

clean-generic:

distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)

maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am

clean-am: clean-generic clean-libLTLIBRARIES clean-libtool \
	clean-noinstLTLIBRARIES mostlyclean-am

distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-libtool distclean-tags

dvi: dvi-am

dvi-am:

html: html-am

info: info-am

info-am:

install-data-am: install-libhighguiincludeHEADERS

install-exec-am: install-libLTLIBRARIES

install-info: install-info-am

install-man:

installcheck-am:

maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic

mostlyclean: mostlyclean-am

mostlyclean-am: mostlyclean-compile mostlyclean-generic \
	mostlyclean-libtool

pdf: pdf-am

pdf-am:

ps: ps-am

ps-am:

uninstall-am: uninstall-info-am uninstall-libLTLIBRARIES \
	uninstall-libhighguiincludeHEADERS

.PHONY: CTAGS GTAGS all all-am check check-am clean clean-generic \
	clean-libLTLIBRARIES clean-libtool clean-noinstLTLIBRARIES \
	ctags distclean distclean-compile distclean-generic \
	distclean-libtool distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-exec install-exec-am install-info \
	install-info-am install-libLTLIBRARIES \
	install-libhighguiincludeHEADERS install-man install-strip \
	installcheck installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic mostlyclean-libtool pdf pdf-am ps ps-am \
	tags uninstall uninstall-am uninstall-info-am \
	uninstall-libLTLIBRARIES uninstall-libhighguiincludeHEADERS

# Tell versions [3.59,3.63) of GNU make to not export all variables.
# Otherwise a system limit (for SysV at least) may be exceeded.
.NOEXPORT:
