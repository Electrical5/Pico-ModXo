# Pi Pico modchip adapter for Original Xbox

This version is based on the ['V1 version'](https://github.com/Team-Resurgent/Modxo) by Team Resurgent (including Shalx)

See the [V0.2 release](https://github.com/Electrical5/Pico-ModXo/releases/tag/V0.2) for the support of the original "[ModXo](https://github.com/shalxmva/modxo)" by Shalx

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
