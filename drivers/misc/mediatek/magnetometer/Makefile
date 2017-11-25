include $(srctree)/drivers/misc/mediatek/Makefile.custom

# In case the platform does NOT support this type of sensors
obj-y   +=  mag.o
obj-y   +=  mag_factory.o



ifeq ($(CONFIG_MTK_AKM09911),y)
obj-y	+=  akm09911/
endif
