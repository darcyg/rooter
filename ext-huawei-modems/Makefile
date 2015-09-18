#Owned by finbarr@Whirlpool
#
#Copyright GNU act.
# See http://www.lteforum.at/mobilfunk/huawei-e3372-openwrt.1739/#post-26074
#
include $(TOPDIR)/rules.mk

PKG_NAME:=ext-huawei-modems
PKG_VERSION:=4.500
PKG_RELEASE:=1

PKG_MAINTAINER:=Created by FB/makefile by finbarr@whirlpool
include $(INCLUDE_DIR)/package.mk

define Package/ext-huawei-modems
  SECTION:=utils
  CATEGORY:=Network
  DEPENDS:=+kmod-usb-net-cdc-eem +kmod-usb-net-cdc-ether \
  		+kmod-usb-net-cdc-mbim +kmod-usb-net-cdc-ncm +kmod-usb-net-cdc-subset \
  		+kmod-usb-net-huawei-cdc-ncm
  TITLE:=Basic packages for huawei usb modems
  PKGARCH:=all
endef

define Package/ext-huawei-modems/description
  Basic packages for huawei usb modems
endef


define Build/Compile
endef


$(eval $(call BuildPackage,ext-huawei-modems))
