# THE LISTENER

This board allow to capture the serial output from the Amiga to a usb/COM port. You can use it along with Diagrom board to diagnose problem on an Amiga motherboard.

Just connect it on the Amiga, open a terminal on Windows or MAC with a program like Putty, choose the COMport number and you will able
to "LISTEN" what the Diagrom has to say.

The board uses an FTDI 232RL chip. This chip does not require any drivers on windows. It will be detected a COMport. Ex COM3. Then on the
Putty configuration, set: COMport number, 9600 BPS and you are done.

# Feedback

If you find any error on this description, please drop me an email to info@arananet.net or If you like the project or want to support it, you can buy me a beer or a KO-FI :) 
[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/H2H51MPWG)

# Updates

27/04/2020: Initial release.

# Note

This is a work in progress, several testing has been made but it should work as is. I take no responsibiltiy for any damage to any equipment that results from the use of this board.

#### I make this available for the Amiga Community! AMIGAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA!.

#### USE AT YOUR OWN RISK!

# Images

<img src="https://github.com/arananet/thelistener/blob/master/img/amiftdi_top.png?raw=true" width="500">

<img src="https://github.com/arananet/thelistener/blob/master/img/amiftdi_bottom.png?raw=true" width="500">

# Bill of materials

| Part          | Value                          | Package                        |
| ------------- | ------------------------------ | ------------------------------ |          
| IC        		| FT232RL                        | FTDI 232RL CHIP                |
| C1        		| 100NF CAPACITOR                | 0805                           |
| C3            | 100NF CAPACITOR                | 0805                           |
| R1        		| 300OHM RESISTOR                | 0805                           |
| RX LED        | SMD LED                        | 0805                           |
| TX LED     		| SMD LED                        | 0805                           |
| USB CONNECTOR | MICRO_USB_4_LEGS               | MICRO_USB_4_LEGS               |
| DB25          | DB25 FEMALE                    | DB25 FEMALE                    |

## USB CONNECTOR

https://lcsc.com/product-detail/USB-Connectors_SHOU-HAN-MICRO-4P-DIP_C456008.html

# License

Shield: [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0
International License][cc-by-sa].

[![CC BY-SA 4.0][cc-by-sa-image]][cc-by-sa]

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

