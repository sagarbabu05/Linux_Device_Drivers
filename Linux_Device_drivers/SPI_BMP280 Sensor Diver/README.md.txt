It can be compiled with:

dtc spidev_disabler.dts -O dtb >spidev_disabler.dtbo


loaded with this comman:

sudo dtoverlay -d . spidev_disabler