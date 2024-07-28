# Pi Pico modchip adapter for Original Xbox

Unofficial board for the original Xbox modchip "[ModXo](https://github.com/shalxmva/modxo)" by Shalx

![3d](https://github.com/Electrical5/Pico-ModXo/blob/main/pico-modxo-3d.png)

# Easy to solder

All components can be soldered 'though hole' at home and the Pico/resistors also have 'surface mount' options, making it ideal for hobbyists or mass production.

![2d](https://github.com/Electrical5/Pico-ModXo/blob/main/pico-modxo-2d.png)

# Fully open source

The KiCad (free application) source files (full schematics!) are included, so you can add/remove components based on your preferences.

![schematics](https://github.com/Electrical5/Pico-ModXo/blob/main/schematics.png)

# SMBus

Currently ModXo doesn't implement reading SMBus via I2C, in the future this could add functionality such as monitoring temperature/fanspeed, LED control or restarting/shutdown the xbox remotely.
Especially if paired with the Pi Pico Wireless, it could allow basic remote control / monitoring of the xbox.
However, there's two solder jumpers to connect the SMBus of the Xbox to the Pi Pico.

# License

You can sell this board as-is, but disclose the source.
If you sell modifications of this board (additional headers for LED strips / LCD / fan), share the modifications under the same license.

# More info

https://github.com/shalxmva/modxo
https://consolemods.org/wiki/Xbox:ModXo
