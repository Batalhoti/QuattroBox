# QuattroBox

<p align="center"><img src=./Images/QuattroBox_View02.jpg width="600"</p>
<p align="center"><img src=./Images/QuattroBox_View01.jpg width="600"</p>
<p align="center"><img src=./Images/QuattroBox_View04.jpg width="600"</p>

# Description

This project is inspired by the Filamentalis and the BoxTurtle, using four modified Filamentalists, each equipped with an independent extruder. The extruders are slightly inclined to optimize the filament path.

The extruder design allows for the use of either NEMA 17 or NEMA 14 motors. However, I have achieved better results with the NEMA 17, so the choice is yours.

The system includes a Y-splitter with a switch and a Binky encoder. Each lane has status LEDs to monitor each filament, and a filament eject button makes it easy to remove the material.

The logo features an LED strip that shows the MMU status (load, unload, and the color of the loaded filament). The entire design is 3D printed, eliminating the need for aluminum extrusions.

The [configuration files](config) in the base folder are provided as an example. Under no circumstance should you replace your own files with these, as they contain your printer's specific configurations


##

I have a Discord channel on [HappyHare](https://discord.gg/pGSMCnBXc7), feel free to ask your questions and give suggestions

E se voce é brasileiro tenho um canal no servidor da [Orion 3D](https://discord.gg/Ap2ZFJXG7s)

##

# **[BOM](./BOM.md)**

# **[MANUAL](./MANUAL.md)**

## My build

[VIDEO 1](https://photos.app.goo.gl/y86quBDpxgd3wVg19)

[VIDEO 2](https://photos.app.goo.gl/qtu92ND3gbf3hNFr5)

<p align="center"><img src=./Images/20241229_232832.jpg width="600"</p>
<p align="center"><img src=./Images/20241229_232458.jpg width="600"</p>
<p align="center"><img src=./Images/20250113_141719.jpg width="600"</p>

## Acknowledgements

Special thanks to SkiBike for the [Filamentalist](https://github.com/Enraged-Rabbit-Community/ERCF_v2/tree/master/Recommended_Options/Filamentalist_Rewinder) design and to ArmoredTurtle for the [BoxTurtle](https://github.com/ArmoredTurtle/BoxTurtle) design, both of which inspired this project.
I also thank Diem who helped me with the publication here on GitHub


## Change log

### v0.1  -  01-13-2025

* Extruder update

* Update CAD

### v0.01 - 01-15-2025

* Update box (only a few details, if you have already printed it, no need to reprint)

* Box divided into 4 parts for those with printers smaller than 300mm

* Update of 'tensioner_mount_load' the wire path has been increased

### v1.0 - 01-30-2025

* New CAD file, completely redone in Fusion

* New STLs (The old STL files are not compatible with the new version) 

* Option to assemble with 623zz bearing instead of BMG

* The box is 8mm smaller

* The box cover, now divided into 2 parts, is compatible with the box divided into 2 and 4 parts

* 2 logo options: one for printing with MMU (recommended) and another with separate files

* Filamentalist parts and box with identifications to facilitate assembly, thanks to Sinister for the tip

* Button with a hole to adjust the Filamentalist, thanks to Ulta for the tip

* All parts are compatible with 255mm printers

### v1.01 - 03-09-2025

* Latch and Extruder Corrections

    * Latch: new support, extension of the shaft lock

    * Extruder: detail for fitting the new latch, improvements in the ECAS outlet, and extended shaft channel for nema 17

* CAD updated

### v1.1 - 03-30-2025

* The extruder switch and encoder do not need to be soldered. Simply crimp the wires into a 5-pin JST connector

* Improved the fitting of the ECAS encoder

* New design for the Tensioner Arm

* The button now needs to be inserted before positioning the Filamentalist in the box to ensure a more efficient fit

* Added an extra LED on the Tensioner Mount to illuminate the filament. Thanks to Diem for the idea!

* Adjusted the box supports due to issues reported by some users

* Text on the bases of the Filamentalist

* Change in the MMB mounting method, making it easier to route the wires

* Added the MMB v2.0 mount

* CAD updated

### v1.1.1 - 04-20-2025

* Enclosure