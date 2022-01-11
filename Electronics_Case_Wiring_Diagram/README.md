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

My intent is to list the files needed in each Sub-Assembly and indicate which ".stl files" need to be replaced or exchanged for a MODed ".stl" file.  I think an [EXCEL spreadsheet would help with this task and can be found here](../The_.STL_Files/Excel_Spreadsheet_.stl_files).

The [".STL" files for my QUEEN Voron 2.4 build can be found here](../The_.STL_Files/Copy_of_.STLs_forQUEEN_As_Built_will-not-be-updated)

---

## Lesson Learned while doing the "Electronics Case Wiring Diagram" for QUEEN:

I finished the AC wiring diagram for the QUEEN build today. From doing the wiring diagram
I determined that I needed to make some adjustements in my power supplies and do more work with the 3D model layout.

I have decided to split the Wiring Diagram for my Voron 2.4 printer up into two wiring diagrams: "AC Electrical Wiring Diagram" and "DC Electrical Wiring Diagram".

The "DC Electrical Wiring Diagram" will show how to setup the Octopus Pro board and all the DC wiring not included in the "Wiring Harness Diagram" like LEDs, fans, DC light switches and so on. I will work on this one next.

The first draft of the "AC Electrical Wiring Diagram" is done and is now being published.  I still might need to make changes to it once I start working on the DC wiring diagram.  Please remember this whole repository is a "Work in progress" because I still have not finished building my Voron 2.4 printer. I have all the building material but I want to document how I will be interconnecting all the modules before I start putting things together.

### Requirements for my Voron 2.4 printer build

One of the requirements for my Voron 2.4 printer is that I want to be able to reboot the Voron 2.4 printer without requiring a reboot of Mainsail or Fluidd (the Raspberry Pi) along with the printer's motherboard and power supplies.  To accomplish this goal, I have decided that my Raspberry Pi will always remain powererd up. It can be shut down through the BIG RED mushroom button but typically it will always be turned on while the Voron 2.4 printer may not be turned on.

I also want to use some extra features with my Voron 2.4 printer, like, filament runout sensor, filament jam detection, automtic shutdown after print job has finished, and resume 3D print after power failure.

The filament runout sensor and filament jam detection will be looked at when I do the DC wiring diagram for the electronic case (which I will be working on next).  The "automatic shutdown after print job has finished" and "resume 3D print after power failure" features needed to be looked at while doing the AC electrical wiring.

These two features have been incorporated into the AC electrical wiring diagram.  I am using BTT's relay V1.2 to perform the "automatic shutdown after print finishes" feature ~~and I am using BTT's UPS module to perform the "resume 3D print after power failure" feature.~~  I also added in another set of relays to allow the Raspberry Pi to remotely shutdown the Voron 2.4 printer (along with the PSU, except for the PSU that supplies 5VDC power for the Raspberry Pi). I also have a mechanical Hour-counter and Engergy Meter incorporated in the front and side skirt of my Voron 2.4 printer that I need to control.  The Energy Meter will always be on when the Voron 2.4 printer is powered up (it is located on the right-hand side of my printer).  The mechanical Hour-Counter will only run when the Voron 2.4 printer is actually producing a 3D part and is located on the front skirt.  This way I can see the number of actual hours of print time. This Hour-Counter runs through a relay so I can control when it is turned on.

The BTT's V1.2 are relays that are normally opened (NO) so when I added my additional relay I needed to ensure that I could configure it to be NO or NC.  The relay that controls the Hour-counter is NO type of relay.

I also want the capability to use momentary switches on the left-hand side and right-hand side of my printer to power up or down the Voron 2.4.  These momentary switches are active low and are hardwired directly into the relays so that software is not needed to control them.  I call these my "hardware reboot switches".  These switches will only reboot the Voron 2.4 (not the Raspberry Pi).  The switch that is on the back of the Voron 2.4 will reboot both the Raspberry Pi and the Voron 2.4 printer.  I will also mount a "mini Red push button (momentary switch)" to one of the keyholes on the Voron 2.4 skirt which allows me to reboot the Voron 2.4 printer via the BTT's V1.2 relay modules.

Since I want the Raspberry Pi to be "alway ON", I need to buy another 5V power supply.  I decided to remove the UHP-200-12 PSU and replace that unit with a PSU that is two PSUs in one unit.  I bought a Meanwell RD-50A PSU which has a 5VDC PSU (@ 6 Amps) and 12VDC PSU (@ 2Amps) in one metal box.  Since the Stealthburner has been realeased as a beta, I have added it to my Voron 2.4 printer and ended up switching all my LEDs from 12VDC to 5VDC.  I will be using Adafruit Neopixels LEDs only and they only work at 5 Volts.  So I down sized my 12V supply and doubled my 5V power supply.

The Meanwell RS-25-5 will be the power supply that always remains on and is attached to the external UPS [APC 1500VA UPS Battery Backup and Surge Protector, BX1500M Power Supply](https://www.amazon.com/gp/product/B06VY6FXMM) along with Voron 2.4 printer.  I am using a "BIG RED" button or mushroom button between the APC UPS unit and the power input (filtered power inlet) for the Voron 2.4 printer.  I have added this for saftey reasons.  The mushroom box assembly will have a long power cord so I can place it where ever I want.  I also have smoke detector located above the 3D printer.

In my AC wiring diagram you will see things like "grounding straps" and "Ferrite core filters".  These are present to help reduce cross talk.

Logically I have 5 power supplies, two 5V PSU, one 12V PSU, one 24V PSU and one 48V PSU.  One PSU combines two of these into one PSU (Meanwell RD-50A combines a 5V PSU and 12V PSU into one PSU).

In the AC electrical wiring diagram some of the lines are thicker than the others. I did this on purpose so that you will automatically recognize the AC lines from the DC lines.  The AC lines are thicker and are distributed using UK2.5 terminal blocks (or Dinkle DK4N termainal blocks).  The DC lines are thin and use WAGO nuts for distrubution blocks.

Since the Raspberry Pi is a 3.3V logic device, I use [3.6V Zener Diodes](https://www.amazon.com/Chanzon-34-Values-Zener-Assorted/dp/B07BTWBXJ3) for over voltage protection on the Raspberry Pi's GPIO lines when using a 5VDC power supply for the 4-channel relay module to activate the relay's coils. Even tho my AC wiring diagram shows I will be using a 4-channel relay module, I might only install a one channel relay module. The resons for going to one channel is that I do not need a 4-channel relay module and I have a one channel relay module sitting in a drawer.

Below you will find the JPG and the PDF files for the "Voron 2.4 AC Electrical Wiring Diagram".

After finding a [schematic diagram of the BTT relay V1.2 from a russian website](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Resources/BTT%20Relay%20V1.2%20Schematic.pdf) I have become aware that I can control the PSUs with the Raspberry Pi via the BTT Relay V1.2 modules without the use of a second relay module. Therefore the secondary relay module will only control the mechanical Hour-Counter.  I have updated my AC Electrical Wiring Diagram to reflect this change.

After a discussion in the Voron discord channel with other more experienced Voron users the following question arose: "Does the Voron 2.4 printer even have the capacity to resume print?  If the Gantry sags at all it won't, since you wouldn't be able to perform QGL with a buildplate already occupied.".  Due to this fact using the BTT UPS modules is now out since I will not be able to get the flying gantery back to where it needs to be to resume a print.  I will be removing the "resume after power failure" as a requirement for my Voron 2.4 printer.

Also another Voron user found an error in my first AC wiring diagram. I forgot to tie all my V- (DC negative voltage) terminals together to establish a common voltage reference between different power supplies. The revised AC wiring diagram now has the V- terminals all tied together.

1/9/2022:

Ok, folks I have some explaining to do. But be aware that now I will be discussing **TWO** different Voron 2.4 printer builds in this build log.

I was watching the build of the Voron 2.4 LDO kit on [@Steve Builds](https://www.youtube.com/channel/UC8VsL6u5PiOgy6n4I4b4Ufw) and have been very very impressed with the LDO kit.  So after discussng my options with my husband we decided that the best route forward for me is to buy the LDO kit and build the LDO 300mm³ build.  I still planning on building the 250mm³ QUEEN build but to build QUEEN I need a work horse 3D printer that prints ABS really well.

Now you are thinking that is nuts. Not really! I added up the cost of just getting the 3D printed parts done by a commerical vendor and the cost is over $5,000.  So the cost of the LDO kit is only $1,350. So instead of paying someone else to print the QUEEN ABS parts I will get a new Voron 2.4 LDO 300mm³ Build which I will call "Voron_LDO" and print the ABS parts for QUEEN myself on the Voron_LDO printer.  This way I get more experience with the printer profiles. I will also be able to print the modified parts and test them out.

I will also have another printer that I can modifiy once the QUEEN build is finished.

I like to think of this rationalization as a way to boot strap my Voron printer experience.  Wink Wink.

1/11/2022:

I am still working on the DC wiring Diagram for the QUEEN build.  Here is what I am trying to figure out right now. 

I have bought a [ERCF v1.1 moster kit - 6 chart version](https://deepfriedhero.in/products/enraged-rabbit-carrot-feeder-v1-1-monster-kit?variant=41260783534249) because I will someday print out the parts and but it together to do multi-material printing.

When planning the QUEEN build I want to ensure that the parts I use for the X-Axis and the toolhead will accomodate the ERCF v1.1. The ERCF adds on additional equipment that the "ERCF Easy Board" will handle. The ["ERCF Easy Board"](https://deepfriedhero.in/products/ercf-ez-board) can be setup in Klipper as an additional MCU and that way the board's PIN definitions can be used.

The reason I choose the [Hartk's ERCF v.3 toolhead board](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit) is that I knew I already purchase the ERCF V1.1 monster kit.

So now that I provided the background story, what am I confused about? Well, after reading the manual for the ["ERCF Easy Board"](https://deepfriedhero.in/products/ercf-ez-board) I learned that I have the following connections available:

On the [ERCF Easy Board, page 93,  I see](http://nbviewer.jupyter.org/github/EtteGit/EnragedRabbitProject/blob/main/Documentation/ERCF_Manual.pdf#page=93):

    1.  "Servo";
    2.  "Selector Motor";
    3.  "Gear Motor";

On the [ERCF Easy Board, page 94,  I see](http://nbviewer.jupyter.org/github/EtteGit/EnragedRabbitProject/blob/main/Documentation/ERCF_Manual.pdf#page=94):

    4.  "Selector Endstop";
    5.  "Encoder";

Besides the ERCF prep for the QUEEN build, I also want to prep QUEEN for the Voron Stealthburner fan assembly.  To use the LEDs on the Stealthburner we need a Data PIN on the Hartk's ERCF v.3 toolhead board along with GND and 5VDC to power the Neopixel LEDs. The [Hartk's ERCF v.3 toolhead board](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit) will only works if you are running stock endstop pod, and you need to run [Klicky_Probe](https://github.com/jlas1/Klicky-Probe) (which we are).  Therefore @Hartk1213 says that the following, hookup should be used:

```
Klicky --- XES header
Filament Sensor --- probe header (those can run on 24v)
LEDs --- FS header (5v, S, G)
```

Hartk1213 says ``that should get you ERCF , LEDs and Klicky all at the same time``.

Ok, but if the ["ERCF Easy Board"](https://deepfriedhero.in/products/ercf-ez-board) has the connection for the .....thinking....
I see now, the "Filament Sensor" is the "AH3364Q-P-B Hall effect sensor that is built into the toolhead". Look at [ERCF Easy Board,page 80](http://nbviewer.jupyter.org/github/EtteGit/EnragedRabbitProject/blob/main/Documentation/ERCF_Manual.pdf#page=94)

I plan on using the Bondtech LGX extruder instead of the clockwork1 (CW1) extruder. So I think from typing this all out I now understand how the connections all work.

I need to ensure that for the QUEEN build the correct LGX part is being used. It has to be the 3D part from the ERCF projocet so I can install the [AH3364Q-P-B Hall effect sensor](https://www.diodes.com/assets/Datasheets/AH3364Q.pdf) and run it at 24VDC.

1. Then I can use the "ABL Header" on the [Hartk's ERCF v.3 toolhead board](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit) to connect up the  "AH3364Q-P-B Hall effect sensor" which is built-in to the [LGX_on_AfterBurner_Adapter_ERCF_Sensor.stl](https://github.com/EtteGit/EnragedRabbitProject/blob/main/Filament_Sensor/Stls/LGX/LGX_on_AfterBurner_Adapter_ERCF_Sensor.stl) 3D printed part.BTW, I renamed the file to "LGX_on_AfterBurner_Adapter_ERCF_Sensor_fromERCFproj.stl".

2.  Ensure the [Klicky_Probe](https://github.com/jlas1/Klicky-Probe) is connected to [Hartk's ERCF v.3 toolhead board's](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit) "XES" header.

3.  Connect the Neopixel LEDs for the Stealthburner fan assembly to [Hartk's ERCF v.3 toolhead board's](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit) "FS" connector.

and

4.  I connect "Servo", "Selector Motor", "Gear Motor", "Selector Endstop" and "Encoder", not to the Octopus Pro board, but to the ["ERCF Easy Board"](https://deepfriedhero.in/products/ercf-ez-board) which uses a "Seeeduino XIAO" processor which talks to the Raspberry Pi 4B board via USB connection (USB-C on Seeeduino XIAO to USB-2.0 on the raspberry pi).

The Seeeduino XIAO microcontroller and sensors are powered through the USB C cable from the RaspberryPi USB port while the stepper motor drivers are powered by the ERCF Easy Board's PSU (12/24V) on-board connector.

So all the connection on the ERCF Easy Board will send data to the rapberry pi via USB.  The only connections to the Octopus Pro board we need to make are the following:

1.   Klicky_Probe connected to the "XES" connector of the ERCF v.3 toolhead board to the "STOP_2" endstop connector of the Octopus Pro board.

2.  Built-in "(AH3364Q-P-B) Hall effect sensor" for the LGX_ERCF part connected to the "ABL" connector of the ERCF v.3 toolhead board to the "Probe" connector on the Octopus Pro board with the "Probe Voltage Select" header's Jumper {on the Octopus Pro board} set on the pins that select 24VDC (or the Boards V~in~). Also on the Octopus Pro board ensure the Jumper on the "Probe Type Select" header is REMOVED so that PNP type is used for the "Probe" connector.  The datasheet on the "AH3364Q-P-B Hall effect sensor" states the following:
```
The single open drain output can be switched on with South pole of
sufficient strength. When the magnetic flux density (B) perpendicular
to the package is larger than the operate point (BOP) the output is
switched on (pulled low) and is held on until magnetic flux density B is
lower than the release point (BRP). The output remains switched off
for North pole fields to or no magnetic fields.
```
This statement indicates to me that the "AH3364Q-P-B Hall effect sensor" works like a "PNP" type Probe. For information on how "PNP" and "NPN" see https://automation-insights.blog/2018/02/14/an-easy-way-to-remember-pnp-and-npn-sensor-wiring/.

3.  Neopixels with an in-line 30 Ohms resistor attached to the first Neopixel which is then attached to the other two Neopixels in the Stealthburner fan assembly get connected to the "FS" connector of the ERCF v.3 toolhead board shih then goes to the "DRIVER_7" stepper motor socket of the Octopus Pro board. The "FS" connector 


Here is a table showing American Wire Gauge current rating: https://www.engineeringtoolbox.com/wire-gauges-d_419.html

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


## A Picture of the "Voron 2.4 AC Electrical Wire Routing Diagram" for QUEEN:

Coming Soon.

I intend to use snapshots from the 3D model I developed for the QUEEN printer, showing you the acutal route I will use for each wire.

<!--- You can download the JPG file for this "Wiring Harness" by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg) and then hit the download button.

Again, to download the PDF just click on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and hit the download button.

 ![JPG of Wiring_Harness](Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) -->

## The PDF file of the "Voron 2.4 AC Electrical Wire Routing Diagram" for QUEEN:

Coming Soon.

I intend to use snapshots from the 3D model I developed for the QUEEN printer, showing you the acutal route I will use for each wire.

<!--- The PDF file looks the same as the JPG file. You can enlarge the image for both file types to get all the details.

You can view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) and then hit the download button.

You can view an even higher resolution image when you view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and then hit the download button. -->

## A Picture of the "Voron 2.4 DC Electrical Wire Routing Diagram" for QUEEN:

Coming Soon.

I intend to use snapshots from the 3D model I developed for the QUEEN printer, showing you the acutal route I will use for each wire.

<!--- You can download the JPG file for this "Wiring Harness" by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg) and then hit the download button.

Again, to download the PDF just click on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and hit the download button.

 ![JPG of Wiring_Harness](Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg) -->

## The PDF file of the "Voron 2.4 DC Electrical Wire Routing Diagram" for QUEEN:

Coming Soon.

I intend to use snapshots from the 3D model I developed for the QUEEN printer, showing you the acutal route I will use for each wire.

<!--- The PDF file looks the same as the JPG file. You can enlarge the image for both file types to get all the details.

You can view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) and then hit the download button.

You can view an even higher resolution image when you view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Voron2.4_My_Build_Log/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and then hit the download button. -->