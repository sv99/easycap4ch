# easycap4ch

somagic easycap - on rpi
init uploads the firmware for the Somagic chip, and reconnects
the USB dongle with a new product ID. 

somagic-easycap nad somagic-easycap-tools - debian source packages

capture initializes the Somagic EasyCAP DC60 or Somagic
EasyCAP002 registers and performs video capture.


## Dependencies
make, gcc, libusb-1.0-0 (and development headers),
libgcrypt11 (and development headers)


## To build from sources
  make && sudo make install


## To build Debian source and binary packages
  apt-get install devscripts debhelper
  debuild -us -uc


## To clean debian directory
  fakeroot debian/rules clean

## v4l2 driver

[github smi2021](https://github.com/Manouchehri/smi2021)
