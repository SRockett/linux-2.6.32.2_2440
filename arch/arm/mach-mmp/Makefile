#
# Makefile for Marvell's PXA168 processors line
#

obj-y				+= common.o clock.o devices.o irq.o time.o

# SoC support
obj-$(CONFIG_CPU_PXA168)	+= pxa168.o
obj-$(CONFIG_CPU_PXA910)	+= pxa910.o

# board support
obj-$(CONFIG_MACH_ASPENITE)	+= aspenite.o
obj-$(CONFIG_MACH_ZYLONITE2)	+= aspenite.o
obj-$(CONFIG_MACH_TAVOREVB)	+= tavorevb.o
obj-$(CONFIG_MACH_TTC_DKB)	+= ttc_dkb.o
