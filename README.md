# QuattroBox

<p align="center"><img src=./Images/QuattroBox_V1_View02.jpg width="600"</p>
<p align="center"><img src=./Images/QuattroBox_View01.jpg width="600"</p>
<p align="center"><img src=./Images/QuattroBox_View04.jpg width="600"</p>

# Description

This project is inspired by the **Filamentalis** and **BoxTurtle**, combining ideas from both to create a robust multi-material system. It uses four modified Filamentalists, each equipped with an independent extruder slightly inclined to optimize the filament path.

The extruder design supports both NEMA 17 and NEMA 14 stepper motors. While both are compatible, better results have been achieved with NEMA 17 motors, the choice is yours.

### Key Features

- **Two types of extruders available**:
  - **With BMG reduction**, compatible with NEMA 14 and NEMA 17 stepper motors
  - **Without reduction** using NEMA 17 pancake stepper motors  
- **Filament hub** with two options:
  - **With Binky encoder** for precise filament positioning
  - **Without encoder**, for a simpler and more cost-effective solution  
- **Status LEDs** on each filament lane to indicate activity  
- **Dedicated illumination for the filament path** to assist during loading and operation  
- **Filament eject button** for quick material changes  
- **LED strip on the logo**, showing MMU status (loading, unloading, and active filament color)  
- **Filament enclosure**, protecting spools from dust and humidity, keeping materials in optimal condition  
- Fully **3D printed structure** – no aluminum extrusions required  
- Compatible with [**Happy Hare**](https://github.com/moggieuk/Happy-Hare/wiki) for MMU control  

The project uses accessible components, open-source technology, and a modular, customizable design.

##

I have a Discord channel on [HappyHare](https://discord.gg/pGSMCnBXc7), feel free to ask your questions and give suggestions

E se voce é brasileiro tenho um canal no servidor da [Orion 3D](https://discord.gg/Ap2ZFJXG7s)

## [BOM](https://docs.google.com/spreadsheets/d/1ZGWbCGkhVMlmwFGOrBHsaueacvJPoY3-_0yoh2NZEvQ/edit?usp=sharing)

## My build

[VIDEO 1](https://photos.app.goo.gl/y86quBDpxgd3wVg19)

[VIDEO 2](https://photos.app.goo.gl/qtu92ND3gbf3hNFr5)

<p align="center"><img src=./Images/20241229_232832.jpg width="600"</p>
<p align="center"><img src=./Images/20241229_232458.jpg width="600"</p>
<p align="center"><img src=./Images/20250113_141719.jpg width="600"</p>
<p align="center"><img src=./Images/20250420_183852.jpg width="600"</p>
<p align="center"><img src=./Images/20250420_183925.jpg width="600"</p>

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

### v1.2 - 05-16-2025

* Extruders with 2 switches  

* 3 extruder options  

    * With BMG reduction, stepper nema 17  
    * With BMG reduction, stepper nema 14  
    * Without reduction, stepper nema 17 pancake  

* All extruders have a latch with an option to use a 623 bearing instead of the BMG idler (I recommend using the bearing, it makes it quieter)  

* The Filamentalist wheel and base have been modified to accommodate an 80mm shaft, and a spot has been added to place M3 nuts 

* Added a small plug at the connection between the extruder and filamentalist to facilitate extruder installation  

* Right-side box modified to accommodate new connector  

* Connector for CAN bus (supports connecting 2 CAN buses) and USB  

* Changed the name "Encoder" to "Hub"  

* 2 hub options  

    * Hub with encoder  
    * Hub without encoder  

* Hub now uses a 623 bearing instead of a 4mm ball  

* Added places to secure wires on the button  

* Logo uses heat inserts  

* Jig for cutting PTFE  

* Jig for soldering LED wires

* Assembly tips

* Updated BOM  

* Updated CAD  
