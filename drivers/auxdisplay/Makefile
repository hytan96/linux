# SPDX-License-Identifier: GPL-2.0
#
# Makefile for the kernel auxiliary displays device drivers.
#

obj-$(CONFIG_CHARLCD)		+= charlcd.o
obj-$(CONFIG_ARM_CHARLCD)	+= arm-charlcd.o
obj-$(CONFIG_KS0108)		+= ks0108.o
obj-$(CONFIG_CFAG12864B)	+= cfag12864b.o cfag12864bfb.o
obj-$(CONFIG_IMG_ASCII_LCD)	+= img-ascii-lcd.o
obj-$(CONFIG_HD44780)		+= hd44780.o
obj-$(CONFIG_HT16K33)		+= ht16k33.o
obj-$(CONFIG_PANEL)             += panel.o
obj-$(CONFIG_SH1107)		+= sh1107.o
obj-$(CONFIG_OEL9M1027)		+= oel9m1027.o
oel9m1027-y			+= oel9m1027_core.o oel9m1027_fb.o
