# This is free software, licensed under the Apache License, Version 2.0 .

include $(TOPDIR)/rules.mk

PKG_VERSION:=1.0.1
PKG_RELEASE:=3
PKG_LICENSE:=Apache-2.0

LUCI_TITLE:=LuCI Airoha SoC Status (NPU, CPU, Frame Engine)
LUCI_DEPENDS:=+luci-base @TARGET_airoha

# 本包移植到 package/ 下独立编译（原位置在 luci feed 的 applications/ 内，
# 用相对路径引用 ../../luci.mk；放到 package/ 后需指向已安装的 luci feed）
include $(TOPDIR)/feeds/luci/luci.mk

# call BuildPackage - OpenWrt buildroot signature
