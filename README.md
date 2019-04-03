<img src="https://raw.githubusercontent.com/AxMod3DPrint/FB2020/master/Images/FB2020_logo.jpg" />

This is a complete re-work of our [FB2020 CoreXY] (https://github.com/AxMod3DPrint/FB2020) design that fixes any faults that we have noticed over the 3 years we have had these in service in our farm. 

The Changes are listed below, this is by no means a full changelog, but the main changes are listed below:-

Major Changes v2
-----------------

* Belt Alignment - Belts were not in line, motors moved to back of printer.
* All parts redesigned or re-modelled  
* XY Gantry now underslung, due to this Z height is reduced to 120mm. This may change in a future iteration.
* Now Clad on three sides with 3mm Acrylic (Perspex). 
* Electronics now changed to MKS Gen L
* Heated bed changed to Mains Voltage heater and Aluminum Plate
* Due to the above 2 Solid State relays are needed one for PS_ON (optional) and one for the Bed (Manditory)
* Bed Long extrusions changed to 220mm to centralise the bed.
* Bed now has an 6mm Acyrilic or 2mm Aluminum (preferred) laser cut base plate to improve stability and improve ease of levelling.
* Due to the above Z Axis Bed mounting printed parts have had the levelling removed. 
* Z Lead Screw alignment fixed
* Alignment printed tools for Y & Z added. (Can be permanently mounted)
* PEI now recommended build surface. 
* Recommended firmware is now [Klipper](https://github.com/KevinOConnor/klipper)

Reliability, Speed, Accuracy, Open Source
-----------------------------------------

This sums up the FB2020 CoreXY 3D Printer. We use these printers ourselves and wouldn’t sell the kits if we didn’t think they were up to snuff. Our FB2020s have run thousands of hours with very little down time. We print all the FB2020 printed parts on our FB2020s.

Speed & Reliability
-------------------

The FB2020’s heart is the MKS GEN L running the Klipper Firmware. Klipper runs from a Raspberry Pi and offloads all calculations to the Pi. This means the FB2020 is even faster than the v1. It has tried and trusted A4988 Stepper Drivers moving the motors, which can be upgraded to Trinamic TMC 2130 for super quiet operation. With an AxMod 3D Print Drakon Geared extruder powering the filament through the bowden tube into a Genuine E3D v6 Hot end. This makes for a winning combination. The heated bed is a mains voltage heater bonded to Tool Grade 5mm Aluminium Plate which means you can print any material you wan.

Low Maintenance Accuracy
------------------------

Running the E3D v6 and the Drakon Geared Extruder, it’s smooth printing. The FB2020 is capable of layer heights of 60 Microns up to 500 Microns and can print pretty much any filament you can throw at it. 

The Bill of Materials and further infomation can be found in the Wiki.

---

<table border="0px">
<th align="left">
&copy; AxMod 3D Print 2019.
</th>
<tr>
<td>
This documentation describes Open Hardware and is licensed under the CERN OHL v. 1.2.
</td>
</tr>
<tr>
<td>
You may redistribute and modify this documentation under the terms of the
CERN OHL v.1.2. (http://ohwr.org/cernohl). This documentation is distributed
WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF
MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable
conditions
</td>
