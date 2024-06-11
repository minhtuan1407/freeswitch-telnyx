include $(top_srcdir)/build/modmake.rulesam
MODNAME=mod_telnyx_demo

mod_LTLIBRARIES = mod_telnyx_demo.la
mod_telnyx_demo_la_SOURCES  = mod_telnyx_demo.c
mod_telnyx_demo_la_CFLAGS   = $(AM_CFLAGS)
mod_telnyx_demo_la_LIBADD   = $(switch_builddir)/libfreeswitch.la
mod_telnyx_demo_la_LDFLAGS  = -avoid-version -module -no-undefined -shared
