obj-m: module.o

modules:
	make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- -C /home/nikhil/Desktop/linux/ M=`pwd` modules

clean:
	make ARCH=arm CROSS_COMPILE=arm-linux-gnueabihf- -C /home/nikhil/Desktop/linux/ M=`pwd` clean

.phony:
	modules clean
