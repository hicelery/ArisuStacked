# ArisuStacked
CAD files and firmware for a stacked acrylic arisu keyboard.

These files are based on FateNozomi's open source stacked alice case, with some minor tweaks for usability. 
This repo does not contain pcb manufacturing files nor BOM, and the user is highly encouraged to read the original source material.

The changes made are as follows:
Support for 2u Backspace.
Support for Step-caps.
Flex cuts to acrylic plate.
Removed redundant pieces from top files.

These files contain both copies of the undercase supports/angles
Note that if you want to use the full stack of 4 angle pieces, 4 M2.5 x 18mm bolts will replace 4 of the M2.5 x 12mm bolts.
![PXL_20220827_232608146](https://user-images.githubusercontent.com/106979235/188211155-aa842600-fc58-4b9b-aee1-6a596eaed60e.jpg)


Some configuration advice:
Where possible try to steer away from hotswap pcbs, as there are no pcb mounting points hot swap pcb have a tendecy to drop or pop switches out.
Note as the 3mm acryl plate is quite thick, getting switches to sit into a hotswap pcb requires the pcb to sit against the plate.
This causes clearance issues with the stabs and poor sound profile.
This is not an issue with soldered switches, and could be fine with 5 pin switches.

The flex cut plate file remedies this but is designed for 1.5mm material, with the use drilling mounting points themselves.

If using the flex cut plate file (i.e for POM plate) try to use a plate foam in order to keep a gap so that the stabs don't rest on the plate.
