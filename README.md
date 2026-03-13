# LFP-Plate

The LFP Plate is a tool used in the implantation of multi-site Local Field Potential (LFP) electrodes. The design can be customized to each surgery, depending on the desired coordinates and depths of the electrodes. Bundles of electrodes are routed through each hole and fixed in place, then using the length of the "guide rods", are cut to the appropriate height using sharp scissors. 

Guide rods are placed next to the 0.75mm diameter holes (height = depth from bregma + 3 mm). 

There is a 0.6mm handle on the side that is useful during implant preparation and can be easily cut off with clippers once the implant has been prepared.


## Hardware

All files were printed using a Form3+ Printer, using GreyV4 resin

### Post-Print Instructions

After print is finished:
* Submerge parts in a 99% isopropyl alcohol bath for 15 minutes
* Move and submerge parts in a second 99% isopropyl alcohol bath for another 15 minutes
* Put parts into a FormCure V1, at 60°C for 1 hour

## Software

3D models are edited using Autodesk Fusion360, and finished models are sliced (aka rendered) using PreForm Slicer 3.50.2.555

### Key Print Settings
* Adaptive layer thickness
* Default print settings
   * PreForm v2.0, 244rgg-17z7za
* Firmware 2.5.3

Make sure to orient print at a slight angle, and position the guide rods away from the print bed 

# Implant Preparation

Parts:
-	23G needle
-	Tungsten wires (info?)
-	Gold pin - (?)
-	Other pins = silver- attained via breaking up a connector - remove part of the thick part (about half off)
-	Small (details) alligator clips


Steps:
1.	Prepare metal guides for electrodes (~3mm in length, inner diameter: from a 23G needle) - cut them with a razor blade
2.	3D printed map/drive
3.	Cut connector (per number of pins) - eventually the male part will stick out of the head
4.	Cut tungsten wires (2-3 cm) with special scissors 
  a.	Shave off 2mm of the plastic on one end of each wire (see a difference in color - more silver)
5.	Solder each wire to one gold pin
  a.	Use as little of the solder lead as possible
  b.	hold the solder iron close to the tungsten wire and allow it to drip down onto the head of the pin
6.	Route tungsten wires into metal guides (Leave about 0.5 cm between the gold pin and start of metal) and apply super glue to both ends of the metal to keep wires in place. 
7.	Make sure you do not bend the wires!!!
8.	Hold the wires by the metal part using forceps and insert wires and metal guides into the holes on 3D printed part via the opposite side of the ‘legs’ or posts
9.	Cut each wire, with special scissors, to the correct length using posts as guides
10.	Plug each gold pin into the connector. Make note of how they're connected so you know which channel corresponds to what region. (remember to also add the other connections to the map)
11.	Make eeg, emg and ground wires (normal ones). solder to normal pins, plug into connector
12.	Make sure no exposed wires are touching each other
13.	Cement the 3D printed part to connector-
  a.	Think about the placement of the 3D part on the skull and based on this cement it in the best place
14.	Cut off guides posts if you haven't already



Measure impedance and gold plate if needed\
Takes about 30 - 45 minutes. More if you have over 4 implants (best use of time to have more than one and less than 5)

Aiming for less than 20 Kilo-ohms per electrode. (impedance value).\
This is done in the Rothschild lab\
Details of the equipment

Machine generating current is sending it to a saline bath, and then back to the machine. We insert the electros into the saline and measure. The goal is to improve impedance (lower it) by gold plating it. Very important to do it not more than a day before - so the measurements are not off.

1.	Have an alligator holding the connector - and all electors (LFP) in the saline bath
2.	Start by passing an outward current to the saline to clean
3.	Measure impedance from each pin - write those down - can be very far away from desired (~100) - typically need to improve all
4.	Can check that there isn’t signal contamination from any other electrodes. (touch EEG wire and see there is no impedance current) 
5.	Gold plate (many steps)
6.	Then let it rest in another bath of saline for 10-15 mins before you can re-measure
7.	Remeasure in saline
8.	Repeat as needed
9.	Once everything is at a good impedance, protect the implants from dust/damage. Implant within the next 1-2 days (I don’t actually know that the signal quality is worse if you implant later)

Implant on mouse\
Same surgery protocol as any other, but note the following:
  - Drill the holes a little larger so it’s easier to clear the dura without much cortical damage
  - Do dummy screw for the EEG and ground holes (AP: -5.3mm OR -5.6mm; and ~0.2mm ML)
    - try not to get all way -> halfway so the screw is in the skull
  - Then lower the LFP wires.
    - Zero the DV when the longest wire touches the surface of the brain
    - Lower to final position (no need to go super slowly if implanting to the cortex because the wires are fairly thick)
    - If wires bend when they touch brain’s surface, the dura wasn’t cleared well. Raise wires and remove dura, then try again.
  - Cement wires and much of the connector in place
    - Make note of which electrode (and it’s position on the connector) will be implanted in frontal vs parietal EEG (if you will analyze these separately)
  - Then implant EEG and ground screws, and optic fiber
  - Make sure some of the cement surrounds the black part of the connector, because otherwise, the pressure from connecting/disconnecting cables can result in the connector coming off from the implant.

