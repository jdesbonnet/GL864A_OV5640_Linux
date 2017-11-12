# GL864A_OV5640_Linux
Issues relating to Genesys Logic GL864A custom firmware for OV5640 module and Linux UVC driver

## Linux OS

Linux raspberrypi 4.4.50+ #970 Mon Feb 20 19:12:50 GMT 2017 armv6l GNU/Linux


Distributor ID:	Raspbian
Description:	Raspbian GNU/Linux 8.0 (jessie)
Release:	8.0
Codename:	jessie

## Firmware 20171014

Found that this worked with Windows 10, but could only be made to work
very infrequently with Linux. Some sort of timeout error happening during
the initial setup of the video connection.

## Firmware 20171030

This version has has moved us forward from generally unusable with Linux
to being usable under certain conditions. However some issues remain that
we really must resolve before we can signoff.

### Connection to camera sometimes fails



### Frame rate issue

We are seeing something in the order of 3 frames per second. This has been
observed on Windows 10. The following is a few successive frames recorded
with the video record feature of Zoom Meeting.

![](./FW_OV5640_B03_ISO_20151030/f008.jpg)
![](./FW_OV5640_B03_ISO_20151030/f009.jpg)
![](./FW_OV5640_B03_ISO_20151030/f010.jpg)
![](./FW_OV5640_B03_ISO_20151030/f011.jpg)



## Links of interest

* [USB2 tests](http://www.usb.org/developers/tools/usb20_tools/#usb20cv)
* http://www.genesyslogic.com/en/product_view.php?show=44
* http://www.usb.org/developers/tools/usb20_tools/#usb20cv

