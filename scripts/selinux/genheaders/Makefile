# SPDX-License-Identifier: GPL-2.0
hostprogs-y := genheaders

HOSTCFLAGS_genheaders.o += \
        -I$(srctree)/security/selinux/include

always := $(hostprogs-y)
