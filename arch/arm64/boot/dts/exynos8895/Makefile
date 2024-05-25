# SPDX-License-Identifier: GPL-2.0
dtb-$(CONFIG_MACH_EXYNOS8895_DREAMLTE_EUR_OPEN) :=  \
    exynos8895-dreamlte_eur_open_10.dtb
# dtb-$(CONFIG_MACH_EXYNOS8895_DREAMLTE_KOR) :=
dtb-$(CONFIG_MACH_EXYNOS8895_DREAM2LTE_EUR_OPEN) :=  \
    exynos8895-dream2lte_eur_open_10.dtb
# dtb-$(CONFIG_MACH_EXYNOS8895_DREAM2LTE_KOR) := 
dtb-$(CONFIG_MACH_EXYNOS8895_GREATLTE_EUR_OPEN) :=  \
    exynos8895-greatlte_eur_open_06.dtb
# dtb-$(CONFIG_MACH_EXYNOS8895_GREATLTE_KOR) :=

subdir-y	:= $(dts-dirs)

targets += dtbs
DTB_LIST  := $(dtb-y)
always    := $(DTB_LIST)

clean-files := *.dtb*
