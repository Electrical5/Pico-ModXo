# Pi Pico modchip adapter for Original Xbox

Unofficial board for the original Xbox modchip "[ModXo](https://github.com/shalxmva/modxo)" by Shalx

Do note that this version does not include the 3.3V to GPIO8, which is used in the newer version by Team Resurgent to deactive the modchip on 1.6 versions while the xbox is running.

![3d](pico-modxo-3d.png)

# Easy to solder

All components can be soldered 'though hole' at home and the Pico/resistors also have 'surface mount' options, making it ideal for hobbyists or mass production.

![2d](pico-modxo-2d.png)

# Fully open source

The KiCad (free application) source files (full schematics!) are included, so you can add/remove components based on your preferences.

![schematics](schematics.png)

# SMBus

Currently ModXo doesn't implement reading SMBus via I2C, in the future this could add functionality such as monitoring temperature/fanspeed, LED control or restarting/shutdown the xbox remotely.
Especially if paired with the Pi Pico Wireless, it could allow basic remote control / monitoring of the xbox.
However, there's two solder jumpers to connect the SMBus of the Xbox to the Pi Pico.

# License

GNU GENERAL PUBLIC LICENSE
Version 3, 29 June 2007

You can sell this board as-is, but disclose the source.
If you sell modifications of this board (additional headers for LED strips / LCD / fan), share the modifications / source files under the same license.

# More info

https://github.com/shalxmva/modxo
https://consolemods.org/wiki/Xbox:ModXo
