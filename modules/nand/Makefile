################################################################################
#
# Common Variables that already set:
#     LICHEE_KDIR
#     LICHEE_MOD_DIR
#     CROSS_COMPILE
#     ARCH
#
#################################################################################

# Do not use allwinner private variables. But for compatible solution of old build
# scritp, load it as default values. Please remove it in the furture.
# All need setup:
#
# KERNEL_SRC_DIR  (KERNEL_SRC)
# KERNEL_OUT_DIR  (O)
# MODULE_INS_DIR  (INSTALL_MOD_PATH)
# Init all variables
ccflags-y += -I $(srctree)/include/linux/

ifneq ($(CONFIG_AW_NAND),)
obj-$(CONFIG_AW_NAND) += sun55iw3p1/
endif