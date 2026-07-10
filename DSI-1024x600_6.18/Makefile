KERNELDIR ?= /lib/modules/$(shell uname -r)/build/

PWD := $(shell pwd)

obj-m += panel-qdtft-dsi.o

all:
	$(MAKE) -C $(KERNELDIR) M=$(PWD) modules
clean:
	$(MAKE) -C $(KERNELDIR) M=$(PWD) clean
install:
	$(MAKE) -C $(KERNELDIR) M=$(PWD) modules_install
	sudo depmod -a





