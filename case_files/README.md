# fu-keyboard/case_files

## Folder Structure

- `/dxf` contains the DXF drawings of the gaskets and the key plate
- `/step` contains STEP 3D models of the bottom and the top parts of the case as well as the gaskets and the key plate

## Production instructions

### Case Threads

ALL the threads on the case are standard M2. Threads should go inside the holes as deep as possible.

Threads location on the **bottom** part of the case:
![threads_bottom](https://i.imgur.com/ZYYq47l.png)

Threads location on the **top** part of the case:
![threads_top](https://i.imgur.com/J2Ie6XV.png)

### Gaskets

Gaskets should be made of rubber 2.25-2.40mm thick sheet with the *optional* sticky layer at the bottom.

You would need 78 gaskets for both top and the bottom parts of the case.

### Key plate

Can be made out of any sturdy material with the thickness of 1.5mm.

**Aluminium, FR4, steel, brass, carbon fibre** are all viable options.

## Bill of material for assembly

* 1x **bottom** case part
* 1x **top** case part
* 1x **key plate**
* 1x **FU!Keyboard PCB**
* 1x **Unified Daughterboard PCB**
* 1x **Unified Daughterboard Cable** (**25 cm**)
* 78x **gaskets**
* 1x button head **M2x6** screw
* 4x button head **M2x3** screws
* 31x button head **M2x10** screws

**NB:** When choosing screws, make **absolutely sure** that the head diameter (øD on the picture below) is **NO MORE** than 3.5mm

![button_head](https://i.imgur.com/MqrFC1k.jpg)

## Assembly instructions

1. **Insert gaskets** into all gasket locations on top and bottom parts of the case. Make sure that they are sticking out about 0.25-0.40mm creating the "lip" for the key plate to rest on.

![gasket_lips](https://i.imgur.com/ZYRbbU4.png)

2. Using the **M2x3** screws, **secure the Unified Daughterboard PCB** to the bottom part of the case
3. **Plug in** one end of Unified Daughterboard **Cable** to the **Unified Daughterboard PCB**
4. **Partly populate the key plate** with a couple of switches in the corners
5. **Plug the key plate** with the switches onto the **FU!Keyboard PCB**
6. **Finish populating the key plate** with the rest of the switches
7. **Plug in the other end** of the Unified Daughterboard **Cable** to the **FU!Keyboard PCB**
8. **Drop the PCB and the key plate assembly** inside the bottom part of the case, making sure that *a)* all the holes on case are lined up with the corresponding ports on the **FU!Keyboard PCB**, and *b)* that the key plate rests on the gasket lips.
9. Using the **M2x10** screws, screw the top and the bottom parts of the case together from the bottom.
10. Use the **M2x6** near the port Power Adapter (*optional*) plugs into

![plug here](https://i.imgur.com/4f0N8FY.png)

## Case Revision History

REV  |  Description
--|--
1.0  |  Open-source Release version
1.1  |  Added the **fu_bottom_logo.step** file with the logo on the bottom part of the case
