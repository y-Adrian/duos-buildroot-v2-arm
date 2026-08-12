dtb-$(CONFIG_ARCH_CVITEK) += $(foreach dts,$(patsubst %.dts,%.dtb,$(wildcard ${srctree}/${src}/*.dts)),$(notdir ${dts}))

always-y          := $(dtb-y)
subdir-y        := $(dts-dirs)
clean-files     := *.dtb
