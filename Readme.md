
# aasdk

### Brief description
C++ object-oriented library containing implementation of core AndroidAuto(tm) functionalities needed to build headunit software.

### Build Guide
#### Local build instructions for Raspberry Pi

```
sudo apt-get update
sudo apt-get -y install cmake build-essential git

sudo apt-get install -y libboost-all-dev libusb-1.0.0-dev libssl-dev libprotobuf-dev protobuf-c-compiler protobuf-compiler libqt5multimedia5 libqt5multimedia5-plugins libqt5multimediawidgets5 qtmultimedia5-dev libqt5bluetooth5 libqt5bluetooth5-bin qtconnectivity5-dev pulseaudio librtaudio-dev

git clone https://github.com/OpenDsh/aasdk

mkdir aasdk_build; cd aasdk_build
cmake -DCMAKE_BUILD_TYPE=Release ../aasdk
make -j2
sudo make install
```

### Supported functionalities
 - AOAP (Android Open Accessory Protocol)
 - USB transport
 - TCP transport
 - USB hotplug
 - AndroidAuto(tm) protocol
 - SSL encryption

### Supported AndroidAuto(tm) communication channels
 - Media audio channel
 - System audio channel
 - Speech audio channel
 - Audio input channel
 - Video channel
 - Bluetooth channel
 - Sensor channel
 - Control channel
 - Input channel

### License
GNU GPLv3

Copyrights (c) 2018 f1x.studio (Michal Szwaj)

*AndroidAuto is registered trademark of Google Inc.*

### Used software
 - [Boost libraries](http://www.boost.org/)
 - [libusb](http://libusb.info/)
 - [CMake](https://cmake.org/)
 - [Protocol buffers](https://developers.google.com/protocol-buffers/)
 - [OpenSSL](https://www.openssl.org/)
 - [Google test framework](https://github.com/google/googletest)

### Support OpenAuto Pro

Support OpenAuto Pro by buying a license from Bluewave Studios, or donating below
[![Donate](https://img.shields.io/badge/Donate-PayPal-green.svg)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=9YH2QCXZ3YZXJ)

For support of other platforms please contact me at f1xstudiopl@gmail.com
