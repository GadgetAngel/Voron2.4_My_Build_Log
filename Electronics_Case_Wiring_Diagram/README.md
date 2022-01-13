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

Besides the ERCF prep for the QUEEN build, I also want to prep QUEEN for the Voron Stealthburner fan assembly.  To use the LEDs on the Stealthburner we need a Data PIN on the Hartk's ERCF v.3 toolhead board along with GND and 5VDC to power the Neopixel LEDs. The [Hartk's ERCF v.3 toolhead board](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit) will work only if you are running stock endstop pod, and you need to run [Klicky_Probe](https://github.com/jlas1/Klicky-Probe) (which we are).  Therefore @Hartk1213 says that the following, hookup should be used:

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

1. Then I can use the "ABL Header" on the [Hartk's ERCF v.3 toolhead board](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit) to connect up the  "AH3364Q-P-B Hall effect sensor" which is built-in to the [LGX_on_AfterBurner_Adapter_ERCF_Sensor.stl](https://github.com/EtteGit/EnragedRabbitProject/blob/main/Filament_Sensor/Stls/LGX/LGX_on_AfterBurner_Adapter_ERCF_Sensor.stl) 3D printed part.

BTW, I renamed the file to "LGX_on_AfterBurner_Adapter_ERCF_Sensor_fromERCFproj.stl".

2.  Ensure the [Klicky_Probe](https://github.com/jlas1/Klicky-Probe) is connected to [Hartk's ERCF v.3 toolhead board's](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit) "XES" header.

3.  Connect the Neopixel LEDs for the Stealthburner fan assembly to [Hartk's ERCF v.3 toolhead board's](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit) "FS" connector.

and

4.  I connect "Servo", "Selector Motor", "Gear Motor", "Selector Endstop" and "Encoder", not to the Octopus Pro board, but to the ["ERCF Easy Board"](https://deepfriedhero.in/products/ercf-ez-board) which uses a "Seeeduino XIAO" processor which talks to the Raspberry Pi 4B board via USB connection (USB-C on Seeeduino XIAO to USB-2.0 on the raspberry pi).

The Seeeduino XIAO microcontroller and sensors are powered through the USB C cable from the RaspberryPi USB port while the stepper motor drivers are powered by the ERCF Easy Board's PSU (12/24V) on-board connector.

So all the connection on the ERCF Easy Board will send data to the rapberry pi via USB.

#### The only connections to the Octopus Pro board we need to make are the following:

1.   Klicky_Probe connected to the "XES" connector of the ERCF v.3 toolhead board to the "STOP_7" endstop connector of the Octopus Pro board (on the LDO Kit they refer to this as the "Z Probe" line).

2.  Built-in "(AH3364Q-P-B) Hall effect sensor" for the LGX_ERCF part connected to the "ABL" connector of the ERCF v.3 toolhead board to the "Probe" connector on the Octopus Pro board with the "Probe Voltage Select" header's Jumper {on the Octopus Pro board} set on the pins that select 24VDC (or the Board's Vᵢₙ).

    * Also on the Octopus Pro board ensure the Jumper on the "Probe Type Select" header is **REMOVED** so that PNP type is used for the "Probe" connector.  The datasheet on the "AH3364Q-P-B Hall effect sensor" states the following:

```
The single open drain output can be switched on with South pole of
sufficient strength. When the magnetic flux density (B) perpendicular
to the package is larger than the operate point (BOP) the output is
switched on (pulled low) and is held on until magnetic flux density B is
lower than the release point (BRP). The output remains switched off
for North pole fields to or no magnetic fields.
```

This statement indicates to me that the "AH3364Q-P-B Hall effect sensor" works like a "PNP" type Probe. For information on how "PNP" and "NPN" see https://automation-insights.blog/2018/02/14/an-easy-way-to-remember-pnp-and-npn-sensor-wiring/.

3.  Neopixels should have an in-line 300 to 500 Ohm resistor between the RGB header's data output pin and the input to the first NeoPixel. The resistor should be at the end of the wire closest to the NeoPixel(s), not the Octopus Pro board.

Neopixels with an in-line 300 to 500 Ohm resistor attached to the first Neopixel which is then attached to the other two Neopixels in the Stealthburner fan assembly. These Stealthburner NeoPixels get connected to the "FS" connector of the ERCF v.3 toolhead board which then goes to the ~~"DRIVER_7" stepper motor socket~~ RGB header of the Octopus Pro board.

From reading about NeoPixels today and Adafruit's best-practices in using NeoPixels (https://learn.adafruit.com/adafruit-neopixel-uberguide/best-practices), I quote Adafruit:

```
Try to minimize the distance between the controller board and first pixel, so the signal is clear.
A meter or two is usually no problem. Much longer and things can become unreliable. Individual NeoPixels can act as repeaters for long runs.
```

On a Voron 2.4 the distance from the motherboard to the toolhead is over 2 meters which is above Adafruit's recommendation.
So to accomodate this limitation one could place a single NeoPiexel half way down the wiring harness to the toolhead so that it acts as a repeater.

On second thought, I want to have more than one strip of NeoPixels.  I will have the individual NeoPixels for the Stealthburner but I plan on using NeoPixel stips on the sids panel and up in the top of the heated chamber. I also plan on putting a string underneath the printer (lights in the electronics compartment and in the litter box compartment).  Since each Neopixel has its own address, I can use one data line for all these lights.

So with all these Neopixels strings I will have plenty of NeoPixel repeaters in my Voron 2.4 printer QUEEN build. That will not be the case for my Voron 2.4 LDO build.

If for your build, you only want to attach the "Voron Stealthburner" Neopixel LEDs, than I would buy a couple extra single Neopixels LEDs and place them in the wiring harness at which ever location you want to act as a repeater for the Neopixel's on the toolhead (one extra single NeoPixel placed half way down the wiring harness will do the trick).  This way the data line will be boasted and its signal level will not degrade so that the next Neopixel can correctly interpret the previous Neopixel's data transmission.

The "FS" connector comming from the ERCF v.3 toolhead board has one wire that needs to be connected up on the Octopus Pro board (Data line for the Neopixel LED which will be using a 5 Volt logic level {not a 3.3 Volt logic level})

~~But first we must properly configure the "DRIVER_7" stepper motor socket.  Ensure that "DRIVER_7" mode Jumpers are set for UART mode if the rest of the stepper motor driver sockets are configure for SPI mode.  So if you are using the TMC5160_PRO drivers then "DRIVER_0", "DRIVER_1", "DRIVER_2", "DRIVER_3", "DRIVER_4", "DRIVER_5", and "DRIVER_6" will all be configured for SPI mode.~~

~~So set the "DRIVER_7" for UART mode. By configuring the opposite mode for the empty driver socket you are ensuring that the empty driver socket will not interfear with the communication bus of the other 7 driver sockets.~~

~~If you look at the schematic diagram for the Octopus Pro you will see that "DRIVER_7" has a chip select line called "DRIVER7_CS":~~ The Picture below went with the crossed out text, so please ignore it.
 ![DRIVER7_Schematic_Diagram](../images/BTT_OctopusPro_schmatic_forDRIVER_7.jpg)

~~If you follow the "DRIVER7_CS" line you will see it leads you to a device labeled ["TXS0104EPWR"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Resources/TXS0104E%204-Bit%20Bidirectional%20Voltage-Level%20Translator_txs0104e.pdf)~~:
The Picture below went with the crossed out text, so please ignore it.
![DRIVER7_Shiftleveler_to_5Vlogic](../images/BTT_OctopusPro_schmatic_DRIVER7_CS_Shiftleveler.jpg)

~~This "TXS0104EPWR" shifts the DRIVER7_CS signal line from 3.3VDC logic level to 5VDC logic level. Which is what we want for the LEDs data line for the stealthburner fan assembly.~~

~~You might be asking why do you not just use the Octopus Pro RGB header? Well you could. But since the Stealthburner uses Neopixels LEDs, I decided to use Neopixels through out the QUEEN build. Remember that is why I bought in a second 5V PSU.  So to control the other lights with the Octopus Pro board I will need more than one Neopixel Data line.  I just choose to use the DRIVER7_CS line for the stealthburner LEDs because when I am ready to do the other Neopixels I will use the RGB header or the DRIVER7_STEP or the DRIVER7_DIR lines.~~

Since I have learned more about NeoPixels I will be following [Adafruit's recommendations on how to hook up Neopixels](https://learn.adafruit.com/adafruit-neopixel-uberguide/best-practices).

Like I said earlier, The "FS" connector comming from the ERCF v.3 toolhead board has one wire that needs to be connected up to the Octopus Pro board (the NeoPixel's Data line).  As I already stated, I will be using a in-line 300 to 500 Ohm resistor between the RGB header's data output pin and the input to the first NeoPixel.

**Please**, **Please**, put the resistor in-line with the first NeoPixel on the data line before trying to hook up power to the NeoPixels.  If you do not, you could permentaly damage the first NeoPixel and have to rewire the Stealthburner to fix the NeoPixel.

Since I am using an independent external power supply to power my NeoPixel strips (I am not using the Octopus Pro to power the LEDs) I will be placing a large capacitor (500–1000 µF at 6.3 Volts or higher) across the + and – 5VDC terminals of the Meanwell RD-50A PSU.  This is what Adafruit remcommends doing, I qoute them below:

```
Before connecting a NeoPixel strip to ANY source of power, a large capacitor (500–1000 µF at 6.3 Volts or higher) across the + and – terminals provides a small power reservoir for abrupt changes in brightness that the power source might not otherwise handle — a common source of NeoPixel “glitching.” The capacitor also buffers sudden changes in the current drawn by the strip.
```

~~Please, remember to hook up the 5VDC line from the ERCF v.3 toolhead board to the 5V line on the DRIVER7 red socket.  If you do not want to use a Dupont connector for the 5VDC line then use a JST connector and attach it to "STOP_3" connector of Octopus Pro board.~~

Please remember to hook up the 5VDC line from the Meanwell RD-50A PSU to the first NeoPixel 5V DC pad and use "Common V- Ground" (the common ground reference between all the PSU in the build) to the GND pad on the first NeoPixel.

Note: You only need **one** 300 to 500 Ohm resistor between the RGB header's data output pin and the first NeoPixel.  So in my case since I have many NeoPixel LEDs I will do this only to the first NeoPixel that will be located in the bottom electronics case for the QUEEN build.

But for my Voron_LDO build, I will only be placing the Neopixels on the "Voron Stealthburner".  In this case I will probably power the NeoPixels from the Octopus board.  I will buy four (4) individual NeoPixel LEDs for my Voron Stealthburner (in fact I already have them).  I will buy two extra in case I screw up on the soldering and ripe a pad off of one of the NeoPixels boards.  I will place one of the "extra" Neopixels half way down my wiring harness to act as a repeater for the Stealthburner's first Neopixel. So I will place an in-line 300 to 500 Ohm resistor between the (Octopus board) RGB header's data output pin and the "extra" Neopixel.  Remember this in-line resitor must be placed closer to the Neopixel then the RBG header. Since I am **NOT using an independent PSU to power the NeoPixels for the my Voron_LDO build**, I **do not need to use** the large capacitor (500–1000 µF at 6.3 Volts or higher) across the + and – terminals of my PSU.

I hope this procedure is clear.  Again, please place an in-line 300 to 500 Ohm resistor between the (Octopus board) RGB header's data output pin and the first Neopixel board.  You will not damage anything by doing this and in fact you could save the Neopixel board from being damaged.

4.  Now we need to connect the extruder motor up to the Octopus Pro.  The LGX extruder motor will connected to the "E-STEP" connector of the ERCF v.3 toolhead board which then connects to "MOTOR6" connector of the Octopus Pro board.

5.  The "CT" or "Chamber Thermistor" line of the ERCF v.3 toolhead board will connect to the "T1" on the Octopus Pro board.

6.  The "TH0" or "Hotend Thermistor" line of the ERCF v.3 toolhead board will connect to the "T0" on the Octopus Pro board.

7.  The "PCF" or "Parts/Print Cooling Fan" line of the ERCF v.3 toolhead board will connect to the "FAN0" on the Octopus Pro board.

8.  The "HEF" or "Hot-End Fan" line of the ERCF v.3 toolhead board will connect to the "FAN1" on the Octopus Pro board.

9.  The "HE0" or "Hot-End Heater" line of the ERCF v.3 toolhead board will connect to the "HE0" or "HEAT0" on the Octopus Pro board.

10. The "24VDC" line of the ERCF v.3 toolhead board will connect to the "BED POWER IN" on the Octopus Pro board.

11. The "AGND" line of the ERCF v.3 toolhead board will connect to the GND PIN on the Octopus Pro board's "T3" connector.

12.  The "GND" line of the ERCF v.3 toolhead board will connect to the "Voron 2.4 AC Wiring Diagram"'s "Common V- Ground" reference (the point where you attach all the V- terminal of each PSU you have in the Build).

So, thank you for letting me type and figure out how this all connects up.  That is how you connect up the Hartk's ERCF v.3 toolhead board to the Octopus Pro if you are using Stealthburner fan assembly on the LGX extruder with Neopixels, Klicky_Probe (XES),  HEF, HE0, TH0, Chamber Thermistor(CT), PCF, HEF, LGX motor, 5VDC, 24VDC, GND, Analogue GND (AGND) and "Common V-" from all the PSUs (GND).

Next we need to connect up all the motors and endstops:

13. The "X" line of the [Voron 2.4 XY Microswitch Endstop PCB board](https://deepfriedhero.in/products/voron-2-4-xy-microswitch-endstop-pcb) will connect to to the "STOP_0" on the Octopus Pro board.

14. The "Y" line of the [Voron 2.4 XY Microswitch Endstop PCB board](https://deepfriedhero.in/products/voron-2-4-xy-microswitch-endstop-pcb) will connect to to the "STOP_1" on the Octopus Pro board.

15. The "HE1" line of the [Z Endstop PCB for Voron v2.4 board](https://deepfriedhero.in/products/z-endstop-pcb-for-voron-v2-4) (on the LDO Kit they refer to this as the "Nozzle Probe" line) will connect to to the "STOP_2" on the Octopus Pro board.


Motor cables: Please use a LED light to ensure that the pairs of wires for each motor coil are lying next to each other in the motor cable's connector. If the two adjacent wires do not turn on the LED light when you turn the shaft of the motor then you will need to find the appropriate pair of wires and ensure that they are adjacent to each other in the JST connector.  What do I mean by two adjacent wires? Well the JST connector has 4 pins. Pick a starting point, call that "PIN 1" then the next pin adjacent to it in the JST connector is "PIN 2". Place an LED across "PIN 1" and "PIN 2". Turn the stepper motor shaft to see if the LED turns on while you turning the motor's shaft. If the LED turns on then "PIN 1" and "PIN 2" are a coil pair. Now check "PIN 3" and "PIN 4", just to ensure that the second motor coil is working properly. Place the LED across "PIN 3" and "PIN 4", does the LED turn on? Now that you have determined which pairs of wires make up the motor's coils. Place the coil pairs as follows: PIN1 and PIN2 are a coil pair, PIN3 and PIN4 are a coil pair.

16. "A" Motor cable is the motor located in the "Rear Right of Gantry" as if standing in front of an upright printer and looking towards it. Place the "A" Motor cable into "Motor_1" connector on the Octopus Pro board.

17. "B" Motor cable is the motor located in the "Rear Left of Gantry" as if standing in front of an upright printer and looking towards it. Place the "A" Motor cable into "Motor_0" connector on the Octopus Pro board.

18. "Z0" Motor cable is the motor located in the "Front Left" as if standing in front of an upright printer and looking towards it. Place the "A" Motor cable into "Motor_2" connector on the Octopus Pro board.

19. "Z1" Motor cable is the motor located in the "Rear Left" as if standing in front of an upright printer and looking towards it. Place the "A" Motor cable into "Motor_3" connector on the Octopus Pro board.

20. "Z2" Motor cable is the motor located in the "Rear Right" as if standing in front of an upright printer and looking towards it. Place the "A" Motor cable into "Motor_4" connector on the Octopus Pro board.

21. "Z3" Motor cable is the motor located in the "Front Right" as if standing in front of an upright printer and looking towards it. Place the "A" Motor cable into "Motor_5" connector on the Octopus Pro board.

22. Bottom Electronic Compartment Fans.  There are two of these fans please splice them together so that one JST connector will feed both fans. Basically you are creating a Y-cable adapter. The "Bottom Electronic Compartment Fans" are connected into "FAN2" connector on the Octopus Pro board.

23. "Filter/Exhaust Fan for the Nevermore Filter" get connected into "FAN3" connector on the Octopus Pro board.

Now the rest of the hook up is to take care of additional items I have added to this build via Mods: like the  "FANS mod"; additional Neopixel LED lights for my side edge panel lighting; additional Neopixel LED lights for the Bottom Electronics case; additional Neopixel LED lights for the Litter Box mod; additional Neopixel LED lights for the Left and right side of TOP panel; additional Neopixel LED lights for the front and back side of the TOP panel;  multiple SPST switches to control the Neopixels Lights; additional thermistor wires that are attached the cable chain; ADXL35 connections to the Raspberry pi; filament runout sensor;  PT1000 thermistor wires or a PT100 4-wire sensor cable; endocope wires; a spare Hotend Thermistor wires; ethernet keystone connection; Fans for the Litter Box Mod; USB 2.0 & USB 3.0 Keystone connection; and the BTT's TFTpi50 screen hookup to the Raspberry pi. I believe that takes care of all the extra items.

I am tired for now and it looks like I will have to update my wiring harness diagram to reflect the changes to the Klicky probe connection and the Filament Sensor (for ERCF connection) to the Octopus Pro board. I apperently need to swap those two locations. I also need to change the LED hook up on the wiring harness diagram.  I have switched from 24VDC LED lights to only using Neopixel lights (which are 5VDC, GND and a data line).

1/13/2022: After looking into the Octopus V1.0/V1.1 and the Octopus Pro V1.0 board's schematic diagrams, I decided to look further into the RGB header of both boards.

From reading the the [SN74LVC1G125 chip data sheet on page 5](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Resources/sn74lvc1g125.pdf), I decided some bench testing is needed to see what is going on with the SN74LVC1G125 voltage lines and how it is effecting the Octopus' ability to send data appropriatly to the first NeoPixel.

Here is a picture of how I see the problem at this time:

![JPG of Understanding_the_Octopus_RBD_header_issue](../images/Understanding_the_Octopus_RBD_header_issue.jpg)

[Here is the online Voltage drop calculator I used.](https://www.rapidtables.com/calc/wire/voltage-drop-calculator.html)

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