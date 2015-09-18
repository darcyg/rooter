#Owned by finbarr@Whirlpool
#
#Copyright GNU act.
include $(TOPDIR)/rules.mk

PKG_NAME:=ext-modem-basic
PKG_VERSION:=4.500
PKG_RELEASE:=1

PKG_MAINTAINER:=Created by FB/makefile by finbarr@whirlpool
include $(INCLUDE_DIR)/package.mk

define Package/ext-rooter-basic
  SECTION:=utils
  CATEGORY:=Network
  DEPENDS:=+luci +kmod-usb-net +kmod-usb-net-cdc-ether +kmod-usb-net-huawei-cdc-ncm \
	    +kmod-usb-net-cdc-mbim +kmod-usb-net-qmi-wwan +kmod-usb-net-rndis \
	    +kmod-usb-net-sierrawireless +kmod-usb-ohci +kmod-usb-serial \
	    +kmod-usb-serial-option +kmod-usb-serial-sierrawireless \
	    +kmod-usb-uhci +kmod-usb2 +luci-proto-3g +luci \
	    +usb-modeswitch +wireless-tools +wpad-mini +rmbim
  TITLE:=Basic packages for usbmodems
  PKGARCH:=all
endef

define Package/ext-rooter-basic/description
  Helper scripts to enable usb modem interfaces
endef


define Build/Compile
endef

define Package/ext-modem-basic/install
	$(CP) ./files/* $(1)/


endef

$(eval $(call BuildPackage,ext-modem-basic))
