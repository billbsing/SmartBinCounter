# Smart Bin Counter

Arduino based device that uses two ultrasonic distance devices to detect which side of the bin the 
rubbish item was thrown into.

The device shows the current score via an LCD display. 


## Features
* Show 'score' for different sides of the bin.
* Record score every day in EEPROM for up to one month.
* Show date and time if the bin is turned over or is not standing.
* Show date and time overnight to conserve power.

## Hardware

1. Iteaduino UNO - Arduino UNO
2. ITDB02-1.8SP - LCD Display 128 x 160
3. 2 x Ultrasonic Ranging Module HC-SR04
4. Real Time Clock Module (DS1307) V1.1
5. Tilt ball switch


## Build & Install
Install the Arduino development environment, then install [ino](http://inotool.org/).

To build:

`ino build`

to install:

`ino install`
