[![Build Status](https://travis-ci.org/jrbenito/SPIFlashA.svg?branch=master)](https://travis-ci.org/jrbenito/SPIFlashA)
# SPIFlashA

Anarduino Miniwireless version of SPIFlash from LowPowerLab (below).

This works with Spansion S25FL127S 128Mbit. It was designed to be a drop in replacement for Felix version (below) and should provide similar functionalities for the Spansion chip.

The original porting to Spansion chip was done by Robert on his [repository](https://github.com/rrobinet/SPIFlashA/). I cloned Felix repository, applied Robert's version over and upgraded 
to latest version from Felix in order to upmerge Robert's wonderfull work.

SPIFlash
========
Arduino/Moteino library for read/write access to SPI flash memory chips.
This works with 256byte/page SPI flash memory such as the 4MBIT W25X40CLSNIG used on [Moteino](www.moteino.com) for data storage and wireless programming.
<br/>
For instance a 4MBit (512Kbyte) flash chip will have 2048 pages: 256*2048 = 524288 bytes (512Kbytes).
<br/>Minimal modifications should allow chips that have different page size to work.
<br/>DEPENDS ON: Arduino *SPI library*.
<br/>
This library was primarily developed to enable **safe** wireless programming on Moteino nodes and Moteino based applications such as the SwitchMote. This has been documented at [lowpowerlab](http://lowpowerlab.com/blog/category/moteino/wireless-programming/). [Dualoptiboot](https://github.com/LowPowerLab/DualOptiboot) (all Moteinos come with it) and [WirelessProgramming library](https://github.com/LowPowerLab/WirelessProgramming) are required to be able to wirelessly re-flash a remote Moteino.
 
### Installation
Copy the content of this library in the "Arduino/libraries/SPIFlash" folder.
<br />
To find your Arduino folder go to File>Preferences in the Arduino IDE.
<br/>
See [this tutorial](https://www.arduino.cc/en/Guide/Libraries) on installing Arduino libraries.

### License
Copyright (c) 2013 by Felix Rusu <felix@lowpowerlab.com>
<br/><br/>
This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
<br/><br/>
This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
<br/><br/>
You should have received a copy of the GNU General Public License along with this program.  If not, see <http://www.gnu.org/licenses/>.
