# This repositoy uses LFS extension

```
I use Git for Windows with VScode to manage this repository.  I also use Git LFS extensions for all the files.

Install Git with LFS extensions: https://git-lfs.github.com/

To Download the whole repository do the following: select the "Clone or download button" and
click on "paste to clipboard" button so you can place the URL for the GitHub repository
to the clipboard. Now Open Git Bash.  Change the current working directory to the location
where you want the cloned directory.
Type git clone, and then paste the URL you copied earlier.
$ git clone https://github.com/GadgetAngel/Voron2.4_My_Build_Log.git
Press Enter to create your local clone.
Now open Window explorer to the location of local clone.
```
## This whole repository can be downloaded as one large zip file from my Google drive at:  (if downloading via LFS is giving you are hard time)

## xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx


# Electronics Case Wiring Diagram for QUEEN (my Voron 2.4 build):

This repository contains JPG and PDF files for the electronics case for QUEEN.  I am presently working on the "Fuctional Wiring Diagram" for my QUEEN Build.  I am concurrently working on the "Real World" Electronics Case Diagram which will show you the actual routing of all the wires I will use for my QUEEN Build.

---

## Sourcing Guide for my QUEEN Voron 2.4 Build:

[Here is the Excel spreadsheet as a sourcing guide for my Voron 2.4](../QUEEN_Sourcing_BOM).

---

## Fusion 360 CAD files and STEP files:

I have spent 3 months creating the 3D model of my QUEEN Voron 2.4 250mm³ build.

I have used the CAD models from each MOD (listed below) and incorporated the respective MOD's CAD model into my QUEEN Fusion 360 model.  After working in Fusion 360 for the past 3 months I have become aware of a couple of things:

1.  When exporting sub-Assemblies from Fusion 360 in .STEP format the only sub-assemblies that get put into the STEP file are the sub-assemblies that are visable at the time the exported STEP file is created.  So when you use STEP files expect all the sub-assemblies to be visable when you first open up the STEP file.  You will have to turn off the options that you do not want to see after you upload the STEP file to Fusion 360 (or your CAD software).

2. If a MOD did not have a Fusion 360 CAD model, I used the .stl files from the MOD and used Fusion 360 to convert the .stl files into parametric bodies.

3.  If you upload .f3d sub-Assembly file and all sub-assembly options are turn on, then please just turn off the sub-assemblies you do not want to see. Sometimes, I exported the .STEP files at the same time I was creating the .f3d files, so I might have left options turned on so I could save the .STEP file.

4. I have noticed that if one uses the "save a copy as ..." option that parts will loose their postion (x,y,z).  So to create the sub-assemblies I did a  "copy" to the clip board and then placed the clip board contents into a new file and saved that file.


GadgetAngel's Voron 2.4 Fusion 360 CAD model (.f3d) and (.STEP) files:

The full model for QUEEN has a fusion 360 (.f3d) file and STEP file.  The STEP file for the full model has been integrated by myself from all the sub-assemblies STEP files. This way I could check the sub-assembly files to ensure that they were created correctly.

1.  [QUEEN's Voron 2.4 Fusion 360 model and STEP version](../CAD/QUEEN_Voron_2.4_Build_ZIP_files)

2.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Electronics from the Bottom Electronics Case](../CAD/Electronics_forBottom_Electronic_Case/ZIP_files)

3.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for Electronics from the LitterBox Case](./CAD/Electronics_forLitterBox_Case/ZIP_files)

4.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the LEDs](../CAD/LEDs/ZIP_files)

5.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for all Panels & Clips](../CAD/Panel_Mounting/QUEENv98_SubAssmbly_Panel&Clips_ZIP_files)

6.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for different panels, see this directory for additional sub-assemblies](../CAD/Panel_Mounting)

7. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for all Skirts](../CAD/Skirts/QUEENv98_SubAssmbly_ALL_Skirts_ZIP_files)

8. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for different Skirts (i.e., Front Skirt, Left-Side Skirt, etc.), see this directory for additional sub-assemblies](../CAD/Skirts)

9. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for all the mods located under the Heated Bed & a Filament Runout Sensor](../CAD/Under_Heated_Bed/ZIP_files)

10. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for my Z Driver Tensioner Mod](../CAD/Z_Drive/ZIP_files)

11. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Exhaust Filter](../CAD/Exhaust_Filter/ZIP_files)

12.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Frame](../CAD/Frame/ZIP_files)

13. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Gantry](../CAD/Gantry/ZIP_files)

14. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Litter Box Mod and its sub-assemblies, see this directory for additional sub-assemblies](../CAD/Litter_Box_CAD)

15. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Z-Endstop called the "SexBolt Z-Endstop"](../CAD/Z_Endstop/ZIP_files)

16. [QUEEN's Voron 24 Fusion 360 subAssembly model (.f3d) and .STEP version for the BTT piTFT V2.0 articulating arm with display mount](../CAD/Skirts/Front/Middle/ZIP_files)

---

## .STL list of files needed for each MOD:

I will be publishing a folder of .stl files for all the printed parts I am using for my QUEEN build, including the ones from my PIF parts ~~(comming soon)~~.

My intent is to list the files needed in each Sub-Assembly and indicate which ".stl files" need to be replaced or exchanged for a MODed ".stl" file.  I think an EXCEL spreadsheet would help with this task and can be found [here](../The_.STL_Files/Excel_Spreadsheet_.stl_files).

The ".STL" files for my QUEEN Voron 2.4 build can be found [here](../The_.STL_Files/Copy_of_.STLs_forQUEEN_As_Built_will-not-be-updated)

---

## Lesson Learned while doing the "Electronics Case Wiring Diagram" for QUEEN:

I finished the AC wiring diagram for the QUEEN build today. From doing the wiring diagram
I determined that I needed to make some adjustements in my power supplies and do more work with the 3D model layout.

I have decided to split the Wiring Diagram for my Voron 2.4 printer up into two wiring diagrams: "AC Electrical Wiring Diagram" and "DC Electrical Wiring Diagram".

The "DC Electrical Wiring Diagram" will show how to setup the Octopus Pro board and all the DC wiring not included in the "Wiring Harness Diagram" like LEDs, fans, DC light switches and so on. I will work on this one next.

The first draft of the "AC Electrical Wiring Diagram" is done and is now being published.  I still might need to make changes to it once I start working on the DC wiring diagram.  Please remember this whole repository is a "Work in progress" because I still have not finished building my Voron 2.4 printer. I have all the building material but I want to document how I will be interconnecting all the modules before I start putting things together.

### Requirements for my Voron 2.4 printer build

One of the requirements for my Voron 2.4 printer is that I want to be able to reboot the Voron 2.4 printer without requiring me to reboot Mainsail or Fluidd (the Raspberry Pi) along with the printer's motherboard and power supplies.  To accomplish this goal, I have decided that my Raspberry Pi will always remain powererd up. It can be shut down thruogh the BIG RED mushroom button but typically it will always be turned on while the Voron 2.4 printer may not be turned on.

I also want to use some extra features with my Voron 2.4 printer, like, filament runout sensor, filament jam detection, automtic shutdown after print job has finished, and resume 3D print after power failure.

The filament runout sensor and filament jam detection will be looked at when I do the DC wiring diagram for the electronic case (which I will be working on next).  The "automatic shutdown after print job has finished" and "resume 3D print after power failure" features needed to be looked at while doing the AC electrical wiring.

These two features have been incorporated into the AC electrical wiring diagram.  I am using BTT's relay V1.2 to perform the "automatic shutdown after print finishes" feature and I am using BTT's UPS module to perform the "resume 3D print after power failure" feature.  I also added in another set of relays to allow the Raspberry Pi to remotely shutdown the Voron 2.4 printer (along with the PSU, except for the PSU that supplies 5VDC power for the Raspberry Pi). I also have a mechanical Hour-counter and Engergy Meter incorporated in the front and side skirt of my Voron 2.4 printer that I need to control.  The Energy Meter will always be on when the Voron 2.4 printer is powered up (it is located on the right-hand side of my printer).  The mechanical Hour-Counter will only run when the Voron 2.4 printer is actually producing a 3D part and is located on the front skirt.  This way I can see the number of actual hours of print time. This Hour-Counter runs thruogh a relay so I can control when it is turn on.

The BTT's relay V1.2 are relays that are normally closed (NO) so when I added my additional relay I needed to ensure that I could configure it to be NC.  The relay that controls the Hour-counter is NO type of relay.

I also want the capability to use momentary switches on the left-hand side and right-hand side of my printer to power up or down the Voron 2.4.  These momentary switches are active low and are hardwired directly into the relays so that software is not needed to control them.  I call these my "hardware reboot switches".  These switches will only reboot the Voron 2.4 (not the Raspberry Pi).  The switch that is on the back of the Voron 2.4 will reboot both the Raspberry Pi and the Voron 2.4 printer.  I will also mount a "mini Red push button (momentary switch)" to one of the keyholes on the Voron 2.4 skirt which allows me to reboot the Voron 2.4 printer via the BTT's relay V 1.2 modules.

Since I want the Raspberry Pi to be "alway ON" I need to buy another 5V power supply.  I decided to remover the UHP-200-12 PSU and replace that unit with a PSU that is two PSU in one unit.  I bought a Meanwell RD-50A PSU which has a 5VDC PSU (@ 6 Amps) and 12VdC PSU (@ 2Amps) in one metal box.  Since the Stealthburner has been realeased as a beta, I have added it to my Voron 2.4 printer and ended up switching all my LEDs from 12VDC to 5VDC.  I will be using Adafruit Neopixels LEDs only and they only work at 5 Volts.  So I down sized my 12V supply and doubled my 5V power supply.

The Meanwell RS-25-5 will be the power supply that always remains on and is attached to the external UPS [APC UPS 1500VA UPS Battery Backup and Surge Protector, BX1500M Backup Battery Power Supply](https://www.amazon.com/gp/product/B06VY6FXMM) along with Voron 2.4 printer.  I am using a "BIG RED" button or mushroom button between teh APC UPS unit and the power input (filtered power inlet) for the Voron 2.4 printer.  I am using this for saftey reason only.  The mushroom box assembly will have a long power cord so I can place it where ever I want to.  I also have smoke detector located above the 3D printer.

I my AC electrical diagram you will see thing like "grounding straps" and "Ferrite core filters".  These are present to help reduce cross talk.

Logically I have 5 power supplies, two 5V PSU, one 12V PSU, one 24V PSU and one 48V PSU.  One PSU combines two of these into one PSU (Meanwell RD-50A combines a 5V PSU and 12V PSU into one PSU).

In the AC electrical wiring diagram some of the lines are thicker than the others. I did this on purpose so that you will automatically recognize the AC lines from the DC lines.  The AC lines are thicker and are distributed using UK2.5 terminal blocks.  The DC lines are thin and use WAGO nuts for distrubution blocks.

Since the Raspberry Pi is a 3.3V logic device, I use [3.6V Zener Diodes](https://www.amazon.com/Chanzon-34-Values-Zener-Assorted/dp/B07BTWBXJ3) for over voltage protection on the Raspberry Pi's GPIO lines when using a 5VDC power supply for the 4-channel relay module to activate the relay's coils.

Below you will find the JPG and the PDF files for the "Voron 2.4 AC Electrical Wiring Diagram".

After finding a [schematic diagram of the BTT relay V1.2 from a russian website](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Resources/BTT%20Relay%20V1.2%20Schematic.pdf) I have become aware that I can control the PSUs witht the Raspberry Pi via the BTT Relay V1.2 modules with the use of a second relay module. Therefore the secondary relaymodule will only control the mechanical Hour-Counter.  I have updated my AC Electrical Wiring Diagram to reflect this change.

After a discussion in the discord channel with other more experience Voron users the following question arose: "Does your printer even have the capacity to resume print?  If the Gantry sags at all it won't, since you wouldn't be able to perform QGL with a buildplate already occupied.".  Due to this fact using the BTT UPS modules is now out since I will not be able to get the flying gantery back to where it needs to be to resume a print.  I will be removing the "resume after power failure" as a requirement for my Voron 2.4 printer.

## A Picture of the "Voron 2.4 AC Electrical Wiring Diagram" for QUEEN:

You can download the JPG file for the "Voron 2.4 AC Electrical Wiring Diagram" by clicking on the filename ["Voron_2.4_Electronics_Case_Wiring_Diagram_AC_wiring.jpg"](../images/Voron_2.4_Electronics_Case_Wiring_Diagram_AC_wiring.jpg) and then hit the download button.


 ![JPG of Voron2.4_AC_Electrical_Wiring_Diagram](../images/Voron_2.4_Electronics_Case_Wiring_Diagram_AC_wiring.jpg)

## The PDF file of the "Voron 2.4 AC Electrical Wiring Diagram" for QUEEN:

The PDF file looks the same as the JPG file. You can enlarge the image for both file types to get all the details.

To download the PDF just click on the filename ["Voron_2.4_Electronics_Case_Wiring_Diagram_AC_wiring.pdf"](../images/Voron_2.4_Electronics_Case_Wiring_Diagram_AC_wiring.pdf) and hit the download button.


## A Picture of the "Voron 2.4 DC Electrical Wiring Diagram" for QUEEN:

Coming Soon.

<!--- You can download the JPG file for the "Wiring Harness" by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg) and then hit the download button.

Again, to download the PDF just click on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and hit the download button.

 ![JPG of Wiring_Harness](Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) -->

## The PDF file of the "Voron 2.4 DC Electrical Wiring Diagram" for QUEEN:

Coming Soon.

<!--- The PDF file looks the same as the JPG file. You can enlarge the image for both file types to get all the details.

You can view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) and then hit the download button.

You can view an even higher resolution image when you view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and then hit the download button. -->

---

## What is the Litter Box Mod?

Please go to [My Litter Box Mod folder](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/tree/main/Electronics_Case_Wiring_Diagram/Litter_Box_Mod).


## Want more information about the "Litter Box" Mod?

Please go to [My Litter Box Mod folder](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/tree/main/Electronics_Case_Wiring_Diagram/Litter_Box_Mod).


## A Picture of the "Litter Box" "AC Electronics Case Wiring Diagram" for QUEEN:

Coming Soon.

I intend to use snapshots from the 3D model I developed for the QUEEN printer, showing you the acutal route I will use for each wire.

<!--- You can download the JPG file for this "Wiring Harness" by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg) and then hit the download button.

Again, to download the PDF just click on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and hit the download button.

 ![JPG of Wiring_Harness](Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) -->

## The PDF file of the "Litter Box" "AC Electronics Case Wiring Diagram" for QUEEN:

Coming Soon.

I intend to use snapshots from the 3D model I developed for the QUEEN printer, showing you the acutal route I will use for each wire.

<!--- The PDF file looks the same as the JPG file. You can enlarge the image for both file types to get all the details.

You can view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) and then hit the download button.

You can view an even higher resolution image when you view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and then hit the download button. -->

## A Picture of the "Litter Box" "DC Electronics Case Wiring Diagram" for QUEEN:

Coming Soon.

I intend to use snapshots from the 3D model I developed for the QUEEN printer, showing you the acutal route I will use for each wire.

<!--- You can download the JPG file for this "Wiring Harness" by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg) and then hit the download button.

Again, to download the PDF just click on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and hit the download button.

 ![JPG of Wiring_Harness](Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) -->

## The PDF file of the "Litter Box" "DC Electronics Case Wiring Diagram" for QUEEN:

Coming Soon.

I intend to use snapshots from the 3D model I developed for the QUEEN printer, showing you the acutal route I will use for each wire.

<!--- The PDF file looks the same as the JPG file. You can enlarge the image for both file types to get all the details.

You can view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) and then hit the download button.

You can view an even higher resolution image when you view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and then hit the download button. -->