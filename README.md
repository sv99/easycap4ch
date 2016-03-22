# easycap4ch

## somagic-easycap and somagic-easycap-tools

somagic debian source packages from https://code.google.com/p/easycap-somagic-linux/

on rpi needs jessie repository

    sudo apt-get install -t jessie devscripts debhelper
    sudo apt-get install -t jessie libgcrypt11-dev libusb-1.0-0-dev

    debuild -us -uc
    # for cleaning
    fakeroot debian/rules clean

## v4l2 driver

[github smi2021](https://github.com/Manouchehri/smi2021)

## usbsnoop

[usbsoop 1.8](http://benoit.papillault.free.fr/usbsnoop/)
[usbsnoop2libusb.pl](http://lindi.iki.fi/lindi/usb/)

usbsnoop.txt - manual
