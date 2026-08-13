# Soldered-PCAL6416A-MicroPython-Library

| ![GPIO Expander PCAL6416A Breakout](https://soldered.com/cdn/shop/files/333180_photo_0681e1_22c4851e-62d9-4ac0-b393-7b11ff10fa8f.webp) |
| :--------------------------------------------------------------------------------------------------------------------------------: |
|                       [GPIO Expander PCAL6416A Breakout](https://soldered.com/products/gpio-expander-pcal6416ahf)                        |

This I2C GPIO expander adds 16 programmable input/output pins to a microcontroller using just two wires. Built around NXP's PCAL6416A chip, it features two 8-bit ports with configurable pull-up/pull-down resistors and an interrupt output. The board supports both standard (100 kHz) and fast (400 kHz) I2C modes, includes a Qwiic connector for solderless connections, and can drive LEDs directly with up to 25 mA per pin output. Part of the [Qwiic ecosystem](https://soldered.com/collections/qwiic-ecosystem).

## How to install

---

After [**installing the mpremote package**](https://docs.micropython.org/en/latest/reference/mpremote.html), install the library on your board using the following command:

```sh
  mpremote mip install github:SolderedElectronics/Soldered-PCAL6416A-MicroPython-Library
```
Or, if you're running a Windows OS:

```sh
  python -m mpremote mip install github:SolderedElectronics/Soldered-PCAL6416A-MicroPython-Library
```

### Repository Contents

- **pcal6416a.py** - MicroPython driver class
- **package.json** - mip install manifest
- **/Examples** - examples for using the library

### Hardware design

You can find hardware design for this board in PCAL6416A hardware repository.

### Documentation

Access library documentation [here](https://docs.soldered.com/pcal6416a/how-it-works/).

### About Soldered

<img src="https://raw.githubusercontent.com/SolderedElectronics/Soldered-Generic-Arduino-Library/dev/extras/Soldered-logo-color.png" alt="soldered-logo" width="500"/>

At Soldered, we design and manufacture a wide selection of electronic products to help you turn your ideas into acts and bring you one step closer to your final project. Our products are intented for makers and crafted in-house by our experienced team in Osijek, Croatia. We believe that sharing is a crucial element for improvement and innovation, and we work hard to stay connected with all our makers regardless of their skill or experience level. Therefore, all our products are open-source. Finally, we always have your back. If you face any problem concerning either your shopping experience or your electronics project, our team will help you deal with it, offering efficient customer service and cost-free technical support anytime. Some of those might be useful for you:

- [Web Store](https://www.soldered.com/shop)
- [Tutorials & Projects](https://soldered.com/learn)
- [Documentation](https://docs.soldered.com)

### Open-source license

Soldered invests vast amounts of time into hardware & software for these products, which are all open-source. Please support future development by buying one of our products.

Check license details in the LICENSE file. Long story short, use these open-source files for any purpose you want to, as long as you apply the same open-source licence to it and disclose the original source. No warranty - all designs in this repository are distributed in the hope that they will be useful, but without any warranty. They are provided "AS IS", therefore without warranty of any kind, either expressed or implied. The entire quality and performance of what you do with the contents of this repository are your responsibility. In no event, Soldered (TAVU) will be liable for your damages, losses, including any general, special, incidental or consequential damage arising out of the use or inability to use the contents of this repository.

## Have fun!

And thank you from your fellow makers at Soldered Electronics.
