# Easy VCP for STM32
This library is the user-customizable part of the STM32 "Cube" USB CDC library.

It provides a familiar "init / send / receive" API as well as circular buffers,
and has been written to be as efficient and easy to use as possible. It's also very portable.

However, integration into a project is non-trivial. Make sure to read the documentation at :

[**CDC Library Deployment**](https://nefastor.com/microcontrollers/stm32/usb/stm32cube-usb-device-library/cdc-continued/)

This repository is provided in support of the [**Nefastor.com**](https://nefastor.com) website.

If you found this code before finding the website, you should read the website
to know what this is about and how to use it.

Make sure to read the manual.

Make sure to read the license.

The following branches and tags have been validated :

* tag **v1.0** on branch **master** :
  * **STM32F103** on "Blue Pill" module
  * **STM32H743** on ST Nucleo-H743ZI2, USB OTG port
    * Requires opening solder bridges SB76 and SB77. RTFM.


