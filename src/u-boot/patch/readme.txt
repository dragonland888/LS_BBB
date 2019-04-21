替换以下文件
u-boot\board\ti\am335x\board.c   
u-boot\board\ti\am335x\mux.c
u-boot\include\common.h
u-boot\include\configs\am335x_evm.h
#>make distclean
#>make am335x_evm

生成u-boot.img和MLO拷入TF卡，短接启动跳线，或把P8.41与P9.1短接，插入TF卡上电即可以正常进入uboot。