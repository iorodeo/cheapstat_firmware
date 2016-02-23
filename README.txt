cheapstat_firmware

Fork of cheapstat firmware - modified for building on linux. 

Note, the original version of the frimware can be found here
http://web.chem.ucsb.edu/~kwp/cheapstat/CheapStat_Firmware.zip 

Requirements: gcc-avr, binutils-avr, gdb-avr avr-libc avrdude


On ubuntu:
sudo apt-get install gcc-avr binutils-avr gdb-avr avr-libc avrdude


Build/Program: (from within src)

make hex: compile hex file
make flash: install hex file
make program:  compile hex file and install



