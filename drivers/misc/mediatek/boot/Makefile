#
# Copyright (C) 2015 MediaTek Inc.
#
# This program is free software: you can redistribute it and/or modify
# it under the terms of the GNU General Public License version 2 as
# published by the Free Software Foundation.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
# GNU General Public License for more details.
#

ifneq ($(strip $(TARGET_BUILD_VARIANT)),eng)
ccflags-y += -DDISABLE_FACTORY_MODE
endif
obj-$(CONFIG_MTK_BOOT) += BOOT_COMMON.o
BOOT_COMMON-$(CONFIG_MTK_BOOT) := mtk_boot_common.o mtk_boot.o
