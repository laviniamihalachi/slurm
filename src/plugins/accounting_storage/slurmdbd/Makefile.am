# Makefile for accounting_storage/slurmdbd plugin

AUTOMAKE_OPTIONS = foreign

PLUGIN_FLAGS = -module -avoid-version --export-dynamic

AM_CPPFLAGS = -I$(top_srcdir) -I$(top_srcdir)/src/common

pkglib_LTLIBRARIES = accounting_storage_slurmdbd.la

# Null job completion logging plugin.
accounting_storage_slurmdbd_la_SOURCES = accounting_storage_slurmdbd.c \
	slurmdbd_agent.c slurmdbd_agent.h
accounting_storage_slurmdbd_la_LDFLAGS = $(PLUGIN_FLAGS)



