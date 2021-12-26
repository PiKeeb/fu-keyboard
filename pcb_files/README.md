# fu-keyboard/pcb_files

## Folder Structure

- `/bom` contains the Bill of Material for PCB in interactive html
- `/gerber` contains the Gerber files for PCB production
- `/kicad_project` contains the KiСad project files
- `/pcb_3dmodel` contains STEP 3D model of the PCB for with most of the components

**NB:** for opening the project files use the following version of KiCad (or newer):

*Version: (6.0.0-0), release build*

## Possible issues with powering SK6812MINI-E

There are ***182*** SK6812MINI-E RGB LEDs on the PCB that might trip the USB over-current protection on your PC. In that case, it's recommended to lower the maximum brightness of the LEDs **AND** to use the powered USB hub.

It's also possible to power the LEDs using the separate power adapter. To do that, you are going to need **5V 40W (8A)** power supply with the **Barrel jack (OD 4.5mm, ID 1mm, positive polarity)**.

You also need to cut the **JP1** jumper on the back of the PCB in order to use the power adapter:

![cut_here](https://i.imgur.com/PMfC4xH.png)

After that's done you can plug the power adapter:

![plug here](https://i.imgur.com/4f0N8FY.png)

## PCB Revision History

REV  |  Description
--|--
1.0  |  Open-source Release version
