<h1 align="center">Duckberry Pi 4</h1>

<div align="center">
  <strong>Turn your Raspberry Pi 4 into a powerful USB Rubber Ducky</strong>
</div>

<br />
<br />

# Overview
I recently got my hands on a raspberry pi 4 and remembered a repo that I'd stumbled upon a couple of months ago, called [pico-ducky](https://github.com/dbisu/pico-ducky) (which heavily inspired this project). Unfortunately the repo itself doesn't work on other rpis apart from the pico so I decided to try and make my own version.

# Requirements
* A Raspberry Pi 4
* An SD card
* [Balena Etcher](https://www.balena.io/etcher/)
* A monitor would be handy, but everything can be done headlessly too

# Installation

1. Download annd exctract [CircuitPython .DISK.IMG.ZIP for the Rasberry Pi 4](https://circuitpython.org/board/raspberrypi_pi4b/).

2. Flush the image into the SD with Balna Etcher.

3. Insert the SD in the raspberry pi and plug it into your computer via the USB-C port.

4. When the `CIRCUITPY` disk shows up eject it, remove the SD from the pi and insert it back on the computer. *Note: This is an optional step to prevent CircuitPython's autorun feature from running the script every time you edit it*

5. Download and exctract the latest version of [adafruit-circuitpython-bundle-x.x-mpy-YYYYMMDD.zip](https://github.com/adafruit/Adafruit_CircuitPython_Bundle/releases/tag/20220827).

6. Navigate to `lib` in the recently extracted folder and copy `adafruit_hid` to the `lib` folder in your SD.

7. The pi is pretty much on the same level as a ducky now. The only thing left is to find some scripts that I made [here](https://github.com/DENNISDGR/Duckberry-Pi-4/wiki) and paste them into `code.py` or create your own with a bit of python knowlege and the help of the CircuitPython [usb_hid Documentation](https://docs.circuitpython.org/projects/hid/en/latest/).

8. Unplug the SD from the computer insert it back into the raspberry pi and watch the magic happen!

# License
Released under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)

# Finally
### Contribute
If you have any suggestions or want to contribute to the project, please do so on the GitHub repo or via email DENNISDGR@protonmail.com.
Also, if you have any questions, feel free to ask me on Discord (DENNISDGR#4419).

### Support
If you want to support the development of my projects, you can do so by donating in one of the following ways:

* XMR address: 89Rg5gxnuGpbKSCsXfmtnEYPubMP6HkKP9WYXNJNCVinVyvKeY5XGeRFJDK7fhNnSs14yXtGxFivNDSzeJaMaPbXVp4RzAy

* BTC address: bc1q8nsv46auuf8zfreznnp4turhd3weegv87kfxlk

* ETH address: 0x544fA9FBfb488894b1bb3071C0CF06d0B13913B3
