# 1. arm-linux-objcopy -O binary -S sdram.elf sdram.bin  将sdram.elf可执行程序，提取2进制裸机程序sdram.bin
# 2. arm-linux-objdump -D sdram.elf > sdram.dis 将sdram.elf可执行程序，反编译为sdram.dis