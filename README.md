* Kernel module 'hello world' example

- for Raspberry Pi install:
sudo apt install raspberrypi-kernel-headers 
sudo apt install rpi-source

- In Makefile tabs are important, cannot be substituted by multiple spaces,
otherwise this error will occure: makefile:4: *** missing separator. Stop

- To build driver: make

- To install driver: sudo insmod hello.ko

- To check effect: dmesg | tail

- To remove: sudo rmmod hello

- Check again in dmesg
