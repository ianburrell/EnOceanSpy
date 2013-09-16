[![Build Status](https://travis-ci.org/hfunke/EnOceanSpy.png?branch=master)](https://travis-ci.org/hfunke/EnOceanSpy)
EnOceanSpy
==========

Use your Raspberry Pi to log all incoming EnOcean telegrams with an USB300 stick.

Requirements (hardware):
* Raspberry Pi
* EnOcean USB300 (Alternative: EnOcean Pi SoC-Gateway TRX 8051)


Compile EnOceanSpy with the following command

gcc -o EnOceanSpy EnOceanSpy.c

and start it with

./EnOceanSpy 

to log all imcoming telegrams at console

or start it with

./EnOceanSpy > log.txt

to log all incoming telegrams in file 'log.txt'.


Have fun to analyze your environment for EnOcean devices.
