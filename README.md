# MacRedux

Reimaging of the original Macintosh 128k logic board 820-0086-C. 

## Introduction
This project is a re-implementation of a Macintosh 128k logic board. From this, I hope to
derive the 128k/512k hybrid board. Primarily, I expect these would be used to replace
an original logic board that has been damaged. There are several components that are
"unobtanium" without harvesting from another board. These parts include the six
PLDs, the IWM (disk drive controller), the three RC dampers, and the external floppy
connector (a custom-made 19-pin connector that looks like it used the DB13W3 shell size).

## Project Status
The board has been fully plotted but has not been sent to manufacturing. I do not yet 
have access to an original board, so I can't validate certain critical measurements
relating to the rear connectors, the RJ11 jack, and the pushbutton switches on the 
side. I would also look to adjust the component grid based on actual measurements. I
think I'm close, but tweaks will be needed.

## Versions
* v1.0-001: Initial prototype based on original schematic.

## Known Bugs/Issues
* The board contains several DRC errors, mostly due to components encroaching on
eachother ("porch violations"). Not sure whether this was an issue for the original
layout designers, but I expect that some of these will be self-correcting once I
adjust the footprints after measuring an actual board. There will likely be
permanent encroachments given how dense the board is in certain areas.

I would also note that certain components (like the push buttons, keyboard connector, 
and audio jack) are being replaced with what I think are equivalents, so further 
adjustments will be needed for those so that they are positioned properly on the 
planar.



