# Volca Bass Custom Firmware
This page contains firmware modifications I wrote for the Korg Volca Bass synthesizer.
## Version 2.01
### Description
As of the latest release of the Volca firmware from Korg ([version 1.02](https://www.korg.com/us/support/download/software/0/140/4365/)), there are a few bugs in the official code which limit the capabilities of the instrument when modded for MIDI out. The Korg firmware plays all notes at velocity 127 and does not handle slides correctly. My custom firmware fixes these issues and allows it to better control external devices.
### New features
The firmware implements the following features:
* With 2.01 correct velocities are emitted on MIDI out notes, while the the old firmware played all velocities at 127. At the moment it's possible to record velocites only via MIDI input, not with the internal ribbon keypad.
* In 2.01 legatos/slides are played correctly for every note on MIDI out, when the step slide is set on the sequencer. The 1.02 firmware played legatos only when the previous note was the same pitch of the current one, staccatos in all other cases.
* I called this firmware version is 2.01 and it's built on top of Korg's 1.02 version. Future versions os this firmware will be called 2.02, 2.03 etc. If you install 2.01 you will be able to downgrade to Korg's official version.
### Installation
To install this firmware please follow the standard procedure from Korg documented on the official manual.
### Download
Download version 2.01 here:
* [Volca_Bass_0201.wav](Volca_Bass_0201.wav?raw=true)
# Disclaimer
I don't take any responsibilities for possible damage caused by installing the firmware I provide on this page. Use at your own risk, but feel free to contact me if you face any issue and I will try to help you. I leave credits and copyright of the original firmware to Korg, my firmware was released for improving interoperability of the Volca Bass and it's the good of the user community and does not bring me any profit.
# Credits
Many thanks to:
* [Tatsuya Takahashi](https://www.tatsuyatakahashi.com/) and [Korg](https://www.korg.com) for developing great products!
* Emil for releasing the firmware encoding/decoding tools at [his webpage](https://uglyduck.vajn.icu/ep/archive/2018/01/).
* Pajen for giving me hints to begin with and [this thread](https://www.gearslutz.com/board/electronic-music-instruments-and-electronic-music-production/1232112-volca-sample-firmware-hack.html?s=9dd803db3f00c353b81f8eccea4ead0a) about Volca firmware hacking.
