ifneq ($(CONFIG_ARCH_QTI_VM), y)
ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_LAHAINA) += lahaina-rumi-overlay.dtbo \
	lahaina-mtp-overlay.dtbo \
	lahaina-mtp-hsp-overlay.dtbo \
	lahaina-cdp-overlay.dtbo \
	lahaina-qrd-overlay.dtbo \
	lahaina-atp-overlay.dtbo \
	lahaina-hdk-overlay.dtbo \
	lahaina-qrd-hsp-overlay.dtbo \
	lahaina-qrd-module-overlay.dtbo \
	lahainap-mtp-overlay.dtbo \
	lahainap-cdp-overlay.dtbo \
	lahainap-atp-overlay.dtbo \
	lahainap-qrd-overlay.dtbo \
	lahaina-cdp-v2.2-overlay.dtbo \
	lahaina-mtp-v2-overlay.dtbo \
	lahaina-mtp-v2.1-overlay.dtbo

lahaina-rumi-overlay.dtbo-base := lahaina.dtb
lahaina-mtp-hsp-overlay.dtbo-base := lahaina.dtb
lahaina-mtp-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-cdp-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-atp-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-hdk-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-qrd-hsp-overlay.dtbo-base := lahaina.dtb
lahaina-qrd-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-qrd-module-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahainap-mtp-overlay.dtbo-base := lahainap.dtb lahainap-v2.dtb lahainap-v2.1.dtb
lahainap-cdp-overlay.dtbo-base := lahainap.dtb lahainap-v2.dtb lahainap-v2.1.dtb
lahainap-atp-overlay.dtbo-base := lahainap.dtb lahainap-v2.dtb lahainap-v2.1.dtb
lahainap-qrd-overlay.dtbo-base := lahainap.dtb lahainap-v2.dtb lahainap-v2.1.dtb
lahaina-cdp-v2.2-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb \
					lahaina-v2.1.dtb
lahaina-mtp-v2-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb \
					lahaina-v2.1.dtb
lahaina-mtp-v2.1-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb \
					lahaina-v2.1.dtb
else
dtb-$(CONFIG_ARCH_LAHAINA) += lahaina-rumi.dtb \
	lahaina-mtp-hsp.dtb \
	lahaina-mtp.dtb \
	lahaina-cdp.dtb \
	lahaina-atp.dtb \
	lahaina-hdk.dtb \
	lahaina-qrd-hsp.dtb \
	lahaina-qrd.dtb \
	lahaina-qrd-module.dtb \
	lahainap-mtp.dtb \
	lahainap-cdp.dtb \
	lahainap-atp.dtb \
	lahainap-qrd.dtb \
	lahaina-v2-mtp.dtb \
	lahaina-v2-cdp.dtb \
	lahaina-v2-atp.dtb \
	lahaina-v2-hdk.dtb \
	lahaina-v2-qrd.dtb \
	lahaina-v2-qrd-module.dtb \
	lahainap-v2-mtp.dtb \
	lahainap-v2-cdp.dtb \
	lahainap-v2-atp.dtb \
	lahainap-v2-qrd.dtb \
	lahaina-cdp-v2.2.dtb \
	lahaina-v2.1-mtp.dtb \
	lahaina-v2.1-cdp.dtb \
	lahaina-v2.1-atp.dtb \
	lahaina-v2.1-hdk.dtb \
	lahaina-v2.1-qrd.dtb \
	lahaina-v2.1-qrd-module.dtb \
	lahainap-v2.1-mtp.dtb \
	lahainap-v2.1-cdp.dtb \
	lahainap-v2.1-atp.dtb \
	lahainap-v2.1-qrd.dtb \
	lahaina-mtp-v2.dtb \
	lahaina-mtp-v2.1.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_WAIPIO) += waipio-rumi-overlay.dtbo \
	waipio-mtp-pm8008-overlay.dtbo \
	waipio-qrd-pm8008-overlay.dtbo \
	waipio-qrd-pm8010-overlay.dtbo \
	waipio-qrd-pm8010-2s-overlay.dtbo

waipio-rumi-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb
waipio-mtp-pm8008-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb waipio-lte.dtb
waipio-mtp-pm8008-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb waipio-lte.dtb
waipio-qrd-pm8008-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb waipio-lte.dtb
waipio-qrd-pm8010-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb waipio-lte.dtb
waipio-qrd-pm8010-2s-overlay.dtbo-base := waipio.dtb waipiop.dtb waipio-v2.dtb waipiop-v2.dtb
else
dtb-$(CONFIG_ARCH_WAIPIO) += waipio-rumi.dtb \
	waipio-mtp-pm8008.dtb \
	waipio-cdp-pm8008.dtb \
	waipio-qrd-pm8008.dtb \
	waipio-atp-pm8008.dtb \
	waipio-mtp-pm8010.dtb \
	waipio-cdp-pm8010.dtb \
	waipio-qrd-pm8010.dtb \
	waipio-qrd-pm8010-2s.dtb \
	waipio-atp-pm8010.dtb \
	waipiop-mtp-pm8008.dtb \
	waipiop-cdp-pm8008.dtb \
	waipiop-qrd-pm8008.dtb \
	waipiop-mtp-pm8010.dtb \
	waipiop-cdp-pm8010.dtb \
	waipiop-qrd-pm8010.dtb \
	waipiop-hdk-pm8010.dtb \
	waipiop-qrd-pm8010-2s.dtb
# Waipio V2
dtb-$(CONFIG_ARCH_WAIPIO) += waipio-v2-mtp-pm8008.dtb \
	waipio-v2-cdp-pm8008.dtb \
	waipio-v2-qrd-pm8008.dtb \
	waipio-v2-atp-pm8008.dtb \
	waipio-v2-mtp-pm8010.dtb \
	waipio-v2-cdp-pm8010.dtb \
	waipio-v2-qrd-pm8010.dtb \
	waipio-v2-qrd-pm8010-2s.dtb \
	waipio-v2-atp-pm8010.dtb \
	waipiop-v2-mtp-pm8008.dtb \
	waipiop-v2-cdp-pm8008.dtb \
	waipiop-v2-qrd-pm8008.dtb \
	waipiop-v2-mtp-pm8010.dtb \
	waipiop-v2-cdp-pm8010.dtb \
	waipiop-v2-qrd-pm8010.dtb \
	waipiop-v2-hdk-pm8010.dtb \
	waipiop-v2-qrd-pm8010-2s.dtb

# Waipio LTE
dtb-$(CONFIG_ARCH_WAIPIO) += waipio-lte-mtp-pm8008.dtb \
	waipio-lte-cdp-pm8008.dtb \
	waipio-lte-qrd-pm8008.dtb \
	waipio-lte-atp-pm8008.dtb \
	waipio-lte-mtp-pm8010.dtb \
	waipio-lte-cdp-pm8010.dtb \
	waipio-lte-qrd-pm8010.dtb \
	waipio-lte-atp-pm8010.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_NEO) += neo-rumi-overlay.dtbo \
		neo_la-rumi-overlay.dtbo \
		neo-qxr-overlay.dtbo \
		neo-idp-overlay.dtbo \
		neo-atp-overlay.dtbo \
		neo-sg-idp-overlay.dtbo \
		neo-idp-display-overlay.dtbo

neo-rumi-overlay.dtbo-base := neo.dtb
neo_la-rumi-overlay.dtbo-base := neo_la.dtb
neo-qxr-overlay.dtbo-base := neo.dtb
neo-idp-overlay.dtbo-base := neo.dtb
neo-atp-overlay.dtbo-base := neo.dtb
neo-sg-idp-overlay.dtbo-base := neo_la.dtb
neo-idp-display-overlay.dtbo-base := neo.dtb

else
dtb-$(CONFIG_ARCH_NEO) += neo-rumi.dtb \
			neo_la-rumi.dtb \
			neo-qxr.dtb \
			neo-idp.dtb \
			neo-atp.dtb \
			neo-sg-idp.dtb \
			neo-idp-display.dtb

endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_DIWALI) += diwali-idp-overlay.dtbo \
	diwali-idp-amoled-overlay.dtbo \
	diwali-idp-usbc-overlay.dtbo

diwali-idp-overlay.dtbo-base := diwali.dtb diwalip.dtb diwali-lte.dtb
diwali-qrd-overlay.dtbo-base := diwali.dtb diwalip.dtb diwali-lte.dtb
diwali-idp-amoled-overlay.dtbo-base := diwali.dtb diwalip.dtb diwali-lte.dtb
else
dtb-$(CONFIG_ARCH_DIWALI) += diwali-rumi.dtb \
	diwali-idp.dtb \
	diwali-atp.dtb \
	diwali-qrd.dtb \
	diwali-idp-amoled.dtb \
	diwali-idp-usbc.dtb \
	diwali-idp-hsp.dtb \
	diwali-idp-nopmi.dtb \
	diwali-qrd-nopmi.dtb \
	diwalip-idp.dtb \
	diwalip-atp.dtb \
	diwalip-qrd.dtb \
	diwalip-idp-amoled.dtb \
	diwalip-idp-usbc.dtb \
	diwalip-idp-hsp.dtb \
	diwalip-idp-nopmi.dtb \
	diwalip-qrd-nopmi.dtb \
	diwali-lte-idp.dtb \
	diwali-lte-atp.dtb \
	diwali-lte-qrd.dtb \
	diwali-lte-idp-amoled.dtb \
	diwali-lte-idp-usbc.dtb \
	diwali-lte-idp-hsp.dtb \
	diwali-lte-idp-nopmi.dtb \
	diwali-lte-qrd-nopmi.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_CAPE) += cape-mtp-pm8008-overlay.dtbo \
        cape-mtp-120fps-pm8008-overlay.dtbo \
        cape-qrd-pm8008-overlay.dtbo \
        cape-mtp-pm8010-overlay.dtbo \
        cape-mtp-120fps-pm8010-overlay.dtbo \
        cape-qrd-pm8010-overlay.dtbo \
	liuqin-sm8475-pm8008-overlay.dtbo

cape-mtp-pm8008-overlay.dtbo-base := cape.dtb cape-v2.dtb capep.dtb
cape-mtp-120fps-pm8008-overlay.dtbo-base := cape.dtb cape-v2.dtb capep.dtb
cape-qrd-pm8008-overlay.dtbo-base := cape.dtb cape-v2.dtb capep.dtb
cape-mtp-pm8010-overlay.dtbo-base := cape.dtb cape-v2.dtb capep.dtb
cape-mtp-120fps-pm8010-overlay.dtbo-base := cape.dtb cape-v2.dtb capep.dtb
cape-qrd-pm8010-overlay.dtbo-base := cape.dtb cape-v2.dtb capep.dtb
liuqin-sm8475-pm8008-overlay.dtbo-base := cape.dtb cape-v2.dtb capep.dtb

else
dtb-$(CONFIG_ARCH_CAPE) += cape-mtp-pm8008.dtb \
	cape-mtp-120fps-pm8008.dtb \
	cape-mtp-nodisplay-pm8008.dtb \
        cape-cdp-pm8008.dtb \
        cape-cdp-qhd-pm8008.dtb \
        cape-atp-pm8008.dtb \
        cape-qrd-pm8008.dtb \
        cape-v2-mtp-pm8008.dtb \
        cape-v2-cdp-pm8008.dtb \
        cape-v2-atp-pm8008.dtb \
        cape-v2-qrd-pm8008.dtb \
	capep-mtp-pm8008.dtb \
	capep-cdp-pm8008.dtb \
	capep-atp-pm8008.dtb \
        cape-mtp-pm8010.dtb \
        cape-mtp-120fps-pm8010.dtb \
	cape-mtp-nodisplay-pm8010.dtb \
        cape-cdp-pm8010.dtb \
        cape-cdp-qhd-pm8010.dtb \
        cape-atp-pm8010.dtb \
        cape-qrd-pm8010.dtb \
        cape-v2-mtp-pm8010.dtb \
        cape-v2-cdp-pm8010.dtb \
        cape-v2-atp-pm8010.dtb \
        cape-v2-qrd-pm8010.dtb \
	capep-mtp-pm8010.dtb \
	capep-cdp-pm8010.dtb \
	capep-atp-pm8010.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_PARROT) += parrot-rumi-overlay.dtbo \
	parrot-atp-overlay.dtbo \
	parrot-idp-overlay.dtbo \
	parrot-idp-wcn3990-overlay.dtbo \
	parrot-idp-wcn3990-amoled-rcm-overlay.dtbo \
	parrot-idp-wcn6750-amoled-rcm-overlay.dtbo \
	parrot-idp-wcn6750-amoled-overlay.dtbo \
	parrot-idp-nopmi-overlay.dtbo \
	parrot-qrd-overlay.dtbo \
	parrot-qrd-wcn6750-overlay.dtbo \
	parrot-qrd-nopmi-overlay.dtbo

parrot-rumi-overlay.dtbo-base := parrot-wcn3990.dtb
parrot-atp-overlay.dtbo-base := parrot-wcn3990.dtb
parrot-idp-overlay.dtbo-base := parrot-wcn6750.dtb
parrot-idp-wcn3990-overlay.dtbo-base := parrot-wcn3990.dtb
parrot-idp-wcn3990-amoled-rcm-overlay.dtbo-base := parrot-wcn3990.dtb
parrot-idp-wcn6750-amoled-rcm-overlay.dtbo-base := parrot-wcn6750.dtb
parrot-idp-wcn6750-amoled-overlay.dtbo-base := parrot-wcn6750.dtb
parrot-idp-nopmi-overlay.dtbo-base := parrot-wcn6750.dtb
parrot-qrd-overlay.dtbo-base := parrot-wcn3990.dtb
parrot-qrd-wcn6750-overlay.dtbo-base := parrot-wcn6750.dtb
parrot-qrd-nopmi-overlay.dtbo-base := parrot-wcn3990.dtb
else
dtb-$(CONFIG_ARCH_PARROT) += parrot-rumi.dtb \
	parrot-atp.dtb \
	parrot-idp.dtb \
	parrot-idp-wcn3990.dtb \
	parrot-idp-wcn3990-amoled-rcm.dtb \
	parrot-idp-wcn6750-amoled.dtb \
	parrot-idp-nopmi.dtb \
	parrot-idp-wcn6750-amoled-rcm.dtb \
	parrot-qrd.dtb \
	parrot-qrd-wcn6750.dtb \
	parrot-qrd-nopmi.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_HOLI) +=  holi-rumi-overlay.dtbo
dtbo-$(CONFIG_ARCH_HOLI) += holi-rumi-overlay.dtbo \
	holi-mtp-overlay.dtbo \
	holi-cdp-overlay.dtbo \
	holi-cdp-lcd-overlay.dtbo \
	holi-qrd-overlay.dtbo \
	holi-atp-overlay.dtbo \
	holi-mtp-usbc-overlay.dtbo

holi-rumi-overlay.dtbo-base := holi.dtb
holi-mtp-overlay.dtbo-base := holi.dtb
holi-cdp-overlay.dtbo-base := holi.dtb
holi-cdp-lcd-overlay.dtbo-base := holi.dtb
holi-qrd-overlay.dtbo-base := holi.dtb
holi-atp-overlay.dtbo-base := holi.dtb
holi-mtp-usbc-overlay.dtbo-base := holi.dtb
else
dtb-$(CONFIG_ARCH_HOLI) += holi-rumi.dtb \
	holi-mtp.dtb \
	holi-cdp.dtb \
	holi-cdp-lcd.dtb \
	holi-qrd.dtb \
	holi-atp.dtb \
	holi-mtp-usbc.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_SHIMA) +=    \
	shima-rumi-overlay.dtbo \
	shima-idp-overlay.dtbo	\
	shima-atp-overlay.dtbo \
	shima-qrd-overlay.dtbo \
	shima-idps-digital-mics-overlay.dtbo

shima-rumi-overlay.dtbo-base := shima.dtb
shima-idp-overlay.dtbo-base := shima.dtb
shima-atp-overlay.dtbo-base := shima.dtb
shima-qrd-overlay.dtbo-base := shima.dtb
shima-idps-digital-mics-overlay.dtbo-base := shima.dtb
else
dtb-$(CONFIG_ARCH_SHIMA) += shima-rumi.dtb  \
			    shima-idp.dtb   \
			    shima-atp.dtb \
			    shima-qrd.dtb \
			    shima-idps-digital-mics.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SM8150) += \
                sm8150-cdp-overlay.dtbo \
                sa8155-adp-star-overlay.dtbo \
                sa8155p-adp-star-overlay.dtbo \
                sa8155-v2-adp-air-overlay.dtbo \
                sa8155p-v2-adp-air-overlay.dtbo

sm8150-cdp-overlay.dtbo-base := sm8150.dtb sm8150-v2.dtb sm8150p.dtb sm8150p-v2.dtb
sa8155-adp-star-overlay.dtbo-base := sa8155.dtb sa8155-v2.dtb
sa8155p-adp-star-overlay.dtbo-base := sa8155p.dtb sa8155p-v2.dtb
sa8155-v2-adp-air-overlay.dtbo-base := sa8155.dtb sa8155-v2.dtb
sa8155p-v2-adp-air-overlay.dtbo-base := sa8155p.dtb sa8155p-v2.dtb
else
dtb-$(CONFIG_ARCH_SM8150)       += sm8150-cdp.dtb \
        sa8155-adp-star.dtb \
        sa8155p-adp-star.dtb \
        sa8155-v2-adp-star.dtb \
        sa8155p-v2-adp-star.dtb \
        sa8155-v2-adp-air.dtb \
        sa8155p-v2-adp-air.dtb
endif
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_ANORAK) += anorak-rumi-overlay.dtbo
anorak-rumi-overlay.dtbo-base := anorak.dtb
else
dtb-$(CONFIG_ARCH_ANORAK) += anorak-rumi.dtb
endif

ifeq ($(CONFIG_ARCH_LAHAINA), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtb-$(CONFIG_ARCH_QTI_VM) += lahaina-vm-mtp.dtb \
	lahaina-vm-cdp.dtb \
	lahaina-vm-qrd.dtb
endif
endif

dtb-$(CONFIG_ARCH_SDXLEMUR) += sdxlemur-rumi.dtb \
	sdxlemur-cdp.dtb \
	sdxlemur-mtp.dtb

ifeq ($(CONFIG_ARCH_SHIMA), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtb-$(CONFIG_ARCH_QTI_VM) += shima-vm-rumi.dtb \
	shima-vm-atp.dtb \
	shima-vm-idp.dtb \
	shima-vm-qrd.dtb
endif
endif

ifeq ($(CONFIG_ARCH_WAIPIO), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtb-$(CONFIG_ARCH_QTI_VM) += waipio-vm-mtp.dtb \
	waipio-vm-cdp.dtb \
	waipio-vm-qrd.dtb \
        waipio-vm-rumi.dtb \
	waipio-lte-vm-mtp.dtb \
	waipio-lte-vm-cdp.dtb \
	waipio-lte-vm-qrd.dtb
endif
endif

ifeq ($(CONFIG_ARCH_CAPE), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtb-$(CONFIG_ARCH_QTI_VM) += cape-vm-mtp.dtb \
	cape-vm-cdp.dtb \
	cape-vm-cdp-qhd.dtb \
	cape-vm-qrd.dtb
endif
endif

ifeq ($(CONFIG_ARCH_DIWALI), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtb-$(CONFIG_ARCH_QTI_VM) +=  \
	diwali-vm-rumi.dtb \
	diwali-vm-atp.dtb \
	diwali-vm-idp.dtb \
	diwali-vm-qrd.dtb
endif
endif

ifeq ($(CONFIG_ARCH_PARROT), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtb-$(CONFIG_ARCH_QTI_VM) +=  \
	parrot-vm-rumi.dtb
endif
endif

always-y	:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
