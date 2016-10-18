#<b>bbconsole</b>
============
Linux console for BlueBasic (BASIC interpreter for CC2540 and CC2541 Bluetooth LE chips).
See https://github.com/aanon4/BlueBasic for more information.

##Usage:

<b>./bbconsole btaddress</b>  
e.g.  
./bbconsole B4:99:4C:21:5A:97  

Keep all sources at the same level:
git/BlueBasic  
git/bbconsole  
git/BlueBasic-loader  
git/bluez  
  
Needs bluez sources:  
git clone git://git.kernel.org/pub/scm/bluetooth/bluez.git  
cd bluez  
./bootstrap  
./configure  
make  


##On the RaspberryPi, you will also need to install some dependencies:
  
sudo apt-get install automake  
sudo apt-get install libtool  
sudo apt-get install gtk  
sudo apt-get install libdbus-1-dev  
sudo apt-get install udev  
sudo apt-get install libudev-dev  
sudo apt-get install libical-dev  
sudo apt-get install libreadline-dev  



Disclaimer:

This is my dirty hack program. I'm not C hacker at all ;-)
Please feel free to send me PR's to make this program better.

This console works very well on Raspberry Pi V3

