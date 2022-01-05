The 3v3 supply pin on the early Raspberry Pi had a maximum available current of about 50 mA. Enough to power a couple of LEDs or a microprocessor, but not much more.

All Raspberry Pi since the Model B+ can provide quite a bit more, up to 500mA to remain on the safe side, thanks to a switching regulator.

You should generally use the 5v supply, coupled with a 3v3 regulator for 3.3v projects.
