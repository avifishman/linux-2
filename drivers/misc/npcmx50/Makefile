#
# Makefile for Nuvoton Miscellaneous optional drivers
#
obj-$(CONFIG_NPCMX50_GPIO)	         += aess_gpiodrv.o
obj-$(CONFIG_NPCMX50_I2C)	         += aess_i2cdrv.o
obj-$(CONFIG_NPCMX50_ADC)	         += aess_adcdrv.o
obj-$(CONFIG_NPCMX50_PWM)	         += aess_pwmdrv.o
obj-$(CONFIG_NPCMX50_FAN)	         += aess_fansensordrv.o
obj-$(CONFIG_NPCMX50_KCS)	         += aess_kcsdrv.o
obj-$(CONFIG_NPCMX50_BIOS_POST_CODE) += aess_biospostdrv.o
obj-$(CONFIG_NPCMX50_PSPI)	         += aess_sspidrv.o
npcmx50_vdm-y := vdm_module.o vdm_common.o CircularBuffer.o ndelay-loop.o
obj-$(CONFIG_NPCMX50_VDM)	         += npcmx50_vdm.o
