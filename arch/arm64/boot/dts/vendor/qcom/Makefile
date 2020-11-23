ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_KONA) += \
                instantnoodlep-overlay-evb.dtbo \
                instantnoodlep-overlay-t0.dtbo \
                instantnoodlep-overlay-evt1.dtbo \
                instantnoodlep-overlay-dvt.dtbo \
                instantnoodle-overlay-t0.dtbo \
                instantnoodle-overlay-evt1.dtbo \
                instantnoodle-overlay-dvt.dtbo \
                instantnoodlev-overlay-t0.dtbo \
                instantnoodlev-overlay-evt1.dtbo \
                instantnoodlev-overlay-dvt.dtbo \
                kebab-overlay.dtbo

instantnoodlep-overlay-evb.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
instantnoodlep-overlay-t0.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
instantnoodlep-overlay-evt1.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
instantnoodlep-overlay-dvt.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb

instantnoodle-overlay-t0.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
instantnoodle-overlay-evt1.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
instantnoodle-overlay-dvt.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb

instantnoodlev-overlay-t0.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
instantnoodlev-overlay-evt1.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
instantnoodlev-overlay-dvt.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb

kebab-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
