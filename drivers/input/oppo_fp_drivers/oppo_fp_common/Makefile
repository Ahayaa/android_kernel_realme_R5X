ifeq ($(CONFIG_OPPO_FINGERPRINT_QCOM),y)
ifeq ($(CONFIG_PRODUCT_REALME_RMX1911),y)
PROJECT_NAME = 19631
else ifeq ($(CONFIG_PRODUCT_REALME_RMX2030),y)
PROJECT_NAME = 19743
endif
endif

DEFS = -DCONFIG_OPPO_FINGERPRINT_PROJCT=$(PROJECT_NAME)
ccflags-y += $(DEFS)

DEFS_PLATFORM = -DCONFIG_OPPO_FINGERPRINT_PLATFORM=6125

ccflags-y += $(DEFS_PLATFORM)

obj-y     +=  oppo_fp_common.o

