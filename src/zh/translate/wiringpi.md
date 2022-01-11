<!--
---
name: WiringPi
class: interface
type: pinout
url: https://github.com/WiringPi/
github: https://github.com/WiringPi/WiringPi-Python
pincount: 40
pin:
  '3':
    name: WiringPi 8
  '5':
    name: WiringPi 9
  '7':
    name: WiringPi 7
  '8':
    name: WiringPi 15
  '10':
    name: WiringPi 16
  '11':
    name: WiringPi 0
  '12':
    name: WiringPi 1
  '13':
    name: WiringPi 2
  '15':
    name: WiringPi 3
  '16':
    name: WiringPi 4
  '18':
    name: WiringPi 5
  '19':
    name: WiringPi 12
  '21':
    name: WiringPi 13
  '22':
    name: WiringPi 6
  '23':
    name: WiringPi 14
  '24':
    name: WiringPi 10
  '26':
    name: WiringPi 11
  '27':
    name: WiringPi 30
  '28':
    name: WiringPi 31
  '29':
    name: WiringPi 21
  '31':
    name: WiringPi 22
  '32':
    name: WiringPi 26
  '33':
    name: WiringPi 23
  '35':
    name: WiringPi 24
  '36':
    name: WiringPi 27
  '37':
    name: WiringPi 25
  '38':
    name: WiringPi 28
  '40':
    name: WiringPi 29
-->
# WiringPi

WiringPi is an attempt to bring Arduino-wiring-like simplicity to the Raspberry Pi.

The goal is to have a single common platform and set of functions for accessing the Raspberry Pi GPIO across multiple languages. WiringPi is a C library at heart, but it's available to both Ruby and Python users who can "gem install wiringpi" or "pip install wiringpi" respectively.

WiringPi uses its own pin numbering scheme, this page illustrates how WiringPi numbers your GPIO pins.

WiringPi has been deprecated by its original author. For more information about, and support with the ongoing community maintained version and ports, see the WiringPi GitHub org: https://github.com/WiringPi/