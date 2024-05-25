# SPDX-License-Identifier: GPL-2.0
dts-dirs += samsung

subdir-y	:= $(dts-dirs)

targets += dtbs
always    := $(DTB_LIST)

dtbs: $(addprefix $(obj)/, $(DTB_LIST))

clean-files := *.dtb*
