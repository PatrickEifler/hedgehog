# Hedgehog

Hedgehog aims to close the gap between musicians and software developers in order to give them the opportunity to perform and record live music sessions in a professional manner.

It implements a MIDI controller, based on the [Raspberry Pi](https://www.raspberrypi.org/) equipped with the [Sonic Pi](https://github.com/samaaron/sonic-pi) music programming environment.

This MIDI controller communicates with Digital Audio Workstations (DAW), such as [Ableton Live](https://www.ableton.com) or common virtual instruments like [Native Instruments Massive](https://www.native-instruments.com/de/products/komplete/synths/massive/). 

From a developers perspective this MIDI controller serves as the gateway to play any virtual instrument which is installed on the host computer. In practice the developer can slip into any role in the live session, playing any instrument from piano to guitar to drums, whatever he wants to experiment with.



## Setup

### Install Raspbian on Raspberry Pi

* Download [NOOBS](https://www.raspberrypi.org/downloads/noobs/)
  * `wget https://downloads.raspberrypi.org/NOOBS_latest`
* Extract zip file
  * `tar -xzvf /path/to/NOOBS_<version>.zip`
* Copy files to SD card
  * `cp -v -r ~/path/to/NOOBS_<version>/* /your/sd/card`

## Todo

* Install Sonic Pi on Raspberry Pi
* Export MIDI signals from Sonic Pi to Raspberry Pi
* Export MIDI signals from Raspberry Pi via USB to DAW
* Map MIDI signals from Raspberry Pi in DAW to virtual instruments
* Start a live music / coding session
* Record session in DAW
* Arrange, mix and master the session
* Export an awesome track
