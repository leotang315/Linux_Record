# Uboot 
## 1. Uboot的最终目的：启动内核。
## 2. Uboot使用：
		- 解压  tar xjf u-boot-1.1.6.tar.bz2
		- 打补丁 cd u-boot-1.1.6 ；patch -p1 < ../u-boot-1.1.6_jz2440_burn_nor_with_nand_uboot.patch
		- 配置 make 100ask24x0_config
		- 编译 make 
		- 烧写
## 3. Uboot分析：
		
