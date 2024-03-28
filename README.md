# MacRedux

Reimaging of the original Macintosh 128k logic board 820-0086-C. 

## Introduction
This project is a re-implementation of a Macintosh 128k logic board. From this, I hope to
derive the 128k/512k hybrid board. Primarily, I expect these would be used to replace
an original logic board that has been damaged. There are several components that are generally 
"unobtanium" without harvesting from another board. These parts include the six PLDs (of which 
only 2 or 3 may have been decoded per some Google searching), the IWM (disk drive controller), 
the RTC chip (although a clone seems to have been made by someone), three RC dampers, and the 
external floppy connector (a custom 19-pin connector that looks like it used the DB13W3 shell
size). The DB19F was also used on the //gs, Amiga, and NeXT machines, among others. You can 
still occasionally find them on eBay. I purchased 2 just to have them for measurements.

## Project Status
The board has been fully test plotted but has not been sent to manufacturing. I was able to
purchase an original board, so most of the critical measurements have been validated. However,
there still may be minor differences between the original and this version, mostly relating to
the rear connectors, the RJ11 jack, and the pushbutton switches on the side. 

## Versions
* v1.0-001: Initial prototype based on original schematic.

## Known Bugs/Issues
* The board still contains several DRC errors, mostly due to components encroaching on
eachother ("porch violations"). There will likely be permanent encroachments given how
dense the board is in certain areas.

* Certain components (like the push buttons, keyboard connector, and audio jack) 
are being replaced with what I think are current equivalents, so further adjustments could
be needed for those so that they are positioned properly on the planar.

* As of now, the PALs have not been fully decoded. The archive includes a text
file with some notes I've collected on the topic from various places on the Net.



