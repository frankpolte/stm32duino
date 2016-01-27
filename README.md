## monolithic stm32duino full install in a folder


This is a full running (linux-only) monolithic stm32duino installation with all packages needed and the (right now) latest running arduino 1.6.5.

Maybe you have to install the udevrules at your system, as explained in the main doc.

The files you can find in the subfolder:  ./hardware/Arduino_STM32/tools/linux

You can use this installation as it is in your home folder. the preferences.txt and the sketchbook folder are inside the installation.
It doesn't polute your arduino installation.

I wrote a starter bash script which repairs the pathes every start: ./stm32duino

### Installation

 * Anywhere in you home folder: git clone ...
 * maybe install the udevrules
  - the files you can find in the subfolder:  ./hardware/Arduino_STM32/tools/linux.
 * run the stm32duino script inside the folder from anywhere


### Notices
@github-people: I know the repo is big, but I see no better way, because it has to use old versions of arduino libraries/IDE and the installation is therefore quite a hassle.

@programmer-problems: maybe you gat problems with the dfu-util (which is the usb programmer), in this case: take the dfu-util of your linux distribution and exchange the one inside with a link to yours.
