# SPDX-License-Identifier: GPL-2.0
ifeq ($(CONFIG_ARCH_ROCKCHIP), y)

dtbo-$(CONFIG_CPU_RK3588) += \
	rk3588-lubancat-dsi0-1080p-overlay.dtbo \
	rk3588-lubancat-i2c5-m3-overlay.dtbo \
	rk3588-lubancat-i2c6-m3-overlay.dtbo \
	rk3588-lubancat-pwm10-m2-overlay.dtbo \
	rk3588-lubancat-pwm11-m3-overlay.dtbo \
	rk3588-lubancat-pwm14-m2-overlay.dtbo \
	rk3588-lubancat-pwm15-m3-overlay.dtbo \
	rk3588-lubancat-spi0-m2-overlay.dtbo \
	rk3588-lubancat-uart0-m2-overlay.dtbo \
	rk3588-lubancat-dsi0-1024x600-overlay.dtbo 

endif

dtbotxt-$(CONFIG_ARCH_ROCKCHIP) += \
	README.rockchip-overlays.md

targets += $(dtbo-y) $(dtbotxt-y)

always-y		:= $(dtbo-y) $(dtbotxt-y)
clean-files		:= *.dtbo
