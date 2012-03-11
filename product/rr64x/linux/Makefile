# $Id: Makefile,v 1.1 2009/12/31 02:07:50 wsw Exp $
#
# Copyright (C) 2006-2009 HighPoint Technologies, Inc.
# All Rights Reserved.
#

HPT_ROOT := ../../..

C_DEFINES := -DSUPPORT_ARRAY

TARGETNAME := rr64x
TARGETTYPE := KMOD
TARGETMODS := him_magni.o ldm_raid.o partition.o raid0.o raid1.o raid5.o jbod.o
TARGETOBJS := os_linux.o osm_linux.o div64.o hptinfo.o config.o

include $(HPT_ROOT)/inc/linux/Makefile.def

$(TARGETOBJS): osm_linux.h
