### I am preparing the complete manual, meanwhile here are some assembly tips


## PTFE
PTFE measurements for this extruder, use the [PTFE Tools](STLs/tools/PTFE_Tools.stl) to cut  

### Lane 0  

* Filamentalist to extruder  

    * 60mm  

* Extruder to Hub with Encoder  

    * 106mm  

* Extruder to Hub without Encoder  

    * 116mm  

### Lane 1  

* Filamentalist to extruder  

    * 55mm  

* Extruder to Hub with Encoder  

    * 55mm  

* Extruder to Hub without Encoder  

    * 70mm  

### Lane 2  

* Filamentalist to extruder  

    * 55mm  

* Extruder to Hub with Encoder  

    * 55mm  

* Extruder to Hub without Encoder  

    * 70mm  

### Lane 3  

* Filamentalist to extruder  

    * 60mm  

* Extruder to Hub with Encoder  

    * 106mm  

* Extruder to Hub without Encoder  

    * 116mm  


# Wires

### Buttons

Wire measurements for connecting the button switches, considering the central board assembly (as in the CAD)

* LANE 0 = 390mm 

* LANE 1 = 290mm 

* LANE 2 = 290mm

* LANE 3 = 390mm

### LEDs

* LED order:

    * Button 0 > Filamentalist 0 > Button 1 > Filamentalist 1 > Button 2 > Filamentalist 2 > Button 3 > Filamentalist 3 > Logo

* MCU to the first LED = 290mm  

* Button to Filamentalist = 190mm  

* Filamentalist to button = 220mm (I recommend splitting this path and adding a JST specified in the BOM to facilitate assembly)

* To facilitate [LED soldering](STLs/tools/LED_Soldering_Tool.stl), there is a jig to help with this

### Switch Extruders

* LANE 0 = 370mm

* LANE 1 = 240mm

* LANE 2 = 240mm

* LANE 3 = 370mm

### Steppers

* LANE 0 = 330mm

* LANE 1 = 260mm

* LANE 2 = 260mm

* LANE 3 = 330mm

### Hub and Encoder 

* 650mm

### Connector

* Canbus and USB = 460mm


# Pinout

### MMB v1.0
<p align="center"><img src=./Images/img_manual/MMB_V1.jpg width="600"</p>

### MMB v1.1
<p align="center"><img src=./Images/img_manual/MMB_V1.1.jpg width="600"</p>

### MMB v2.0
<p align="center"><img src=./Images/img_manual/MMB_V2.jpg width="600"</p>