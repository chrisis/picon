obj-m := combicon_gpio_rpi2.o
KVERSION := `uname -r`

all:
	$(MAKE) -C /lib/modules/$(KVERSION)/build M=$(PWD) modules

clean: 
	$(MAKE) -C /lib/modules/$(KVERSION)/build M=$(PWD) clean
