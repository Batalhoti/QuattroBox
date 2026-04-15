## Change log

### v2 04-15-2026

- Adjustment of hub cable cover dimensions.  

- Larger wire ducts on the cover.  

- Cover sides adapted for 180mm printers.  

- Mounting holes for the lanes in the box are now oval to facilitate assembly.  

- Heaters: improved AC wire routing, added a Wago connector for the fuse.  

- Removed from the official project the supports for EBB36, RP2040, Wago CAN bus, and Wago 24V; they will remain as extras for those who want to use them.  

- Adjustments to the LED carrier dimensions of the lanes.  

- Mounts for placing the MMU supported by the extrusions on top of the printer

- Box adjustments:  

  - Dimensions of the hub hole.  

  - Dimensions of the duct for exhaust and BME cables. 

  - Locations of cable clips.  

  - Dimensions of the hinge to use a 330mm iron rod. 

  - Spheres for fastening the top mount 


### v2 Beta - 02-16-2026

- Filament dryer with AC heater

- Exhaust fan to remove humid air

- Dedicated 4A power supply (optional, for those who prefer not to use the printer’s power)

- More compact extruder using a NEMA17 23mm (pancake) motor — other motor sizes will require modifications

- Hub with integrated Sync

- New Hub with Sync PSF

- Hinged lid

- Simplified assembly: all electronics are assembled outside the enclosure first, then installed into the case

- Cable management clips

- Optimized for a 180mm footprint with up to 142mm height

- Dedicated space for an RFID reader (still in development)

### v1.2.2.2 - 07-08-2025
- Manual corrections  
  - Heat insert from Filamentalist  
  - Warning about motor shaft dimensions on extruder without gearbox  
  - Screws for the hub with encoder  

### v1.2.2.1 - 06-28-2025
- Manual corrections  
  - Heatset Inserts  
  - Typo  
  - Button wire length  

### v1.2.2 - 06-22-2025
- Assembly manual added to support the build process  
- Updated buttons to avoid sharp edges on internal parts, improving fit and finish  
- Extruder updated with improved switch mounts for better triggering  
- Fixed incorrect label on the `Rear Left Top` part of the enclosure  
- Encoder adjusted to add more spring tension and tolerance, reducing print errors  
- Updated LED logo mount with a clear indicator for LED cable exit position  
- Revised cable channel for the LED logo wiring inside the box  
- Latch updated to use a 623 bearing for smoother operation  
- Added `axle_depth_tool` to assist with assembling the Filamentalis axle  
- Added `calibration_tool.stl` for tuning hole diameters and fits  
- Added `MR85 Insert` tool to help insert the MR85 bearing into the extruder  
- Updated `PTFE_Tools` for more precise PTFE tube cutting  

### v1.2.1 - 05-28-2025
- Support for mounting on the top of the printer with options for Monolith panel and Voron standard  

### v1.2 - 05-16-2025
- Extruders with 2 switches  
- 3 extruder options  
  - With BMG reduction, stepper nema 17  
  - With BMG reduction, stepper nema 14  
  - Without reduction, stepper nema 17 pancake  
- All extruders have a latch with an option to use a 623 bearing instead of the BMG idler  
- The Filamentalist wheel and base modified for 80mm shaft + M3 nuts  
- Added small plug between extruder and filamentalist  
- Right-side box modified for new connector  
- Connector for CAN bus (supports 2 buses) and USB  
- "Encoder" renamed to "Hub"  
- 2 hub options (with/without encoder)  
- Hub now uses MR63 bearing instead of 4mm ball  
- Added wire securing spots on the button  
- Logo uses heat inserts  
- Jig for cutting PTFE  
- Jig for soldering LED wires  
- Assembly tips  
- Updated BOM  
- Updated CAD  

### v1.1.1 - 04-20-2025
- Enclosure  

### v1.1 - 03-30-2025
- Extruder switch and encoder no longer need soldering (5-pin JST connector)  
- Improved ECAS encoder fitting  
- New design for Tensioner Arm  
- Button insertion order changed for better fit  
- Extra LED added on Tensioner Mount  
- Adjusted box supports  
- Text on Filamentalist bases  
- Change in MMB mounting method  
- Added MMB v2.0 mount  
- CAD updated  

### v1.01 - 03-09-2025
- Latch and Extruder Corrections  
  - Latch: new support, extended shaft lock  
  - Extruder: fitting for new latch, ECAS outlet improvements, extended shaft channel for nema 17  
- CAD updated  

### v1.0 - 01-30-2025
- New CAD file, redone in Fusion  
- New STLs (not compatible with old version)  
- Option to assemble with 623zz bearing instead of BMG  
- Box 8mm smaller  
- Box cover divided into 2 parts, compatible with 2 and 4-part box  
- 2 logo options (MMU printing or separate files)  
- Filamentalist parts and box with identifications  
- Button with hole for adjustment  
- All parts compatible with 255mm printers  

### v0.01 - 01-15-2025
- Update box (minor details, no need to reprint)  
- Box divided into 4 parts for printers <300mm  
- Update of 'tensioner_mount_load' with increased wire path  

### v0.1 - 01-13-2025
- Extruder update  
- Update CAD  