#Owned by finbarr@Whirlpool
#
#Copyright GNU act.
include $(TOPDIR)/rules.mk

PKG_NAME:=ext-finbarr-addons
PKG_VERSION:=4.500
PKG_RELEASE:=1

PKG_MAINTAINER:=Created by FB/makefile by finbarr@whirlpool
include $(INCLUDE_DIR)/package.mk

define Package/ext-finbarr-addons
  SECTION:=utils
  CATEGORY:=Network
  DEPENDS:=+luci +luci-mod-rpc +luci-app-ddns \
  		+kmod-usb-net +kmod-usb-net-cdc-ether +kmod-usb-net-huawei-cdc-ncm \
	    +kmod-usb-net-cdc-mbim +kmod-usb-net-qmi-wwan +kmod-usb-net-rndis \
	    +kmod-usb-net-sierrawireless +kmod-usb-ohci +kmod-usb-serial \
	    +kmod-usb-serial-option +kmod-usb-serial-sierrawireless \
	    +kmod-usb-serial-wwan +kmod-usb-uhci +kmod-usb2 +luci-proto-3g +luci \
	    +wireless-tools +wpad-mini +rmbim
  TITLE:=Extra packages for my router
  PKGARCH:=all
endef

define Package/ext-finbarr-addons/description
  Extra packages for my router
endef


define Build/Compile
endef


$(eval $(call BuildPackage,ext-finbarr-addons))
