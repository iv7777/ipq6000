include $(TOPDIR)/rules.mk

ARCH:=aarch64
BOARD:=ipq60xx
BOARDNAME:=Qualcomm Atheros IPQ60xx
FEATURES:=squashfs fpu ramdisk nand
MAINTAINER:=John Crispin <john@phrozen.org>
CPU_TYPE:=cortex-a53
SUBTARGETS:=generic

KERNEL_PATCHVER:=4.4

KERNELNAME:=Image dtbs

include $(INCLUDE_DIR)/target.mk
DEFAULT_PACKAGES += \
	ath11k-firmware-ipq6018 \
	kmod-ath11k-ahb \
	kmod-ath11k-pci \
	autocore-arm \
	kmod-gpio-button-hotplug \
	kmod-leds-gpio \
	kmod-qca-nss-dp \
	kmod-qca-nss-drv \
	kmod-qca-nss-drv-bridge-mgr \
	kmod-qca-nss-drv-pppoe \
	kmod-qca-nss-ecm \
	kmod-qca-ssdk \
	luci-app-cpufreq \
	nss-firmware-ipq6018 \
	qca-ssdk-shell \
	swconfig \
	uboot-envtools \
	wpad-openssl

$(eval $(call BuildTarget))
