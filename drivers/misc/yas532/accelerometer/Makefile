#
# Copyright (c) 2010 Yamaha Corporation
#
# This program is free software; you can redistribute it and/or
# modify it under the terms of the GNU General Public License
# as published by the Free Software Foundation; either version 2
# of the License, or (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program; if not, write to the Free Software
# Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA  02110-1301,
# USA.
#

obj-$(CONFIG_INPUT_YAS_ACCELEROMETER) += yas_acc_kernel_driver.o
ifdef CONFIG_YAS_ACC_MULTI_SUPPORT
obj-$(CONFIG_YAS_ACC_DRIVER_LIS3DH) += yas_acc_driver-lis3dh.o
obj-$(CONFIG_YAS_ACC_DRIVER_BMA250) += yas_acc_driver-bma25x.o
obj-$(CONFIG_YAS_ACC_DRIVER_BMA222E) += yas_acc_driver-bma222e.o
obj-$(CONFIG_YAS_ACC_DRIVER_KXTJ2) += yas_acc_driver-kxtj2.o
endif