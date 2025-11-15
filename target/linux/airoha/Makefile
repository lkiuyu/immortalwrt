include $(TOPDIR)/rules.mk

ARCH:=arm
BOARD:=airoha
BOARDNAME:=Airoha ARM
SUBTARGETS:=en7523 an7581 an7583
FEATURES:=dt squashfs nand ramdisk gpio
FEATURES:=dt squashfs nand ramdisk gpio pci pcie rootfs-part usb

KERNEL_PATCHVER:=6.12

include $(INCLUDE_DIR)/target.mk

$(eval $(call BuildTarget))
