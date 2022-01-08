## This is a Build Log for my Voron 2.4 250 mm DIY 3D Printer called "QUEEN":

My Voron 2.4 3D Printer has a name "QUEEN".

This repository contains wiring diagrams, specification sheets, any documentation I use to complete my Voron 2.4 build. I also am including aesthetic designs for QUEEN's back panel and side panels.

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

## This whole repository can be downloaded as one large zip file from my Google drive at: (if downloading via LFS is giving you are hard time)

## xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

## Mother board I plan on using:

I will be using the Octopus Pro V1.0 board as the mother board for my Voron 2.4 printer.
I will be powering my TMC5160 PRO stepper motor drivers with 48V DC.

## Planning Phase:

I am ~~still planning~~ done planning my Voron 2.4 build.

I have all my PIF parts and sourced all my parts via "sub-kits".  This will be explained later.

I wanted to post an Excel spreadsheet for sourcing all my "sub-kits" or individual items for my Voron 2.4 ~~, but I need to remove it from a bigger spreadsheet I have been using to keep track of a lot of different information.  After I get done with the electronics case wiring diagram, I will work on providing an~~ [Here is the Excel spreadsheet as a sourcing guide for my Voron 2.4](/QUEEN_Sourcing_BOM).

## MODS I plan for QUEEN:

### Fusion 360 CAD files and STEP files:

I have spent 3 months creating the 3D model of my QUEEN Voron 2.4 250mm³ build.

I have used the CAD models from each MOD (listed below) and incorporated the respective MOD's CAD model into my QUEEN Fusion 360 model.  After working in Fusion 360 for the past 3 months I have become aware of a couple of things:

1.  When exporting sub-Assemblies from Fusion 360 in .STEP format the only sub-assemblies that get put into the STEP file are the sub-assemblies that are visable at the time the exported STEP file is created.  So when you use STEP files expect all the sub-assemblies to be visable when you first open up the STEP file.  You will have to turn off the options that you do not want to see after you upload the STEP file to Fusion 360 (or your CAD software).

2. If a MOD did not have a Fusion 360 CAD model, I used the .stl files from the MOD and used Fusion 360 to convert the .stl files into parametric bodies.

3.  If you upload .f3d sub-Assembly file and all sub-assembly options are turn on, then please just turn off the sub-assemblies you do not want to see. Sometimes, I exported the .STEP files at the same time I was creating the .f3d files, so I might have left options turned on so I could save the .STEP file.

4. I have noticed that if one uses the "save a copy as ..." option that parts will loose their postion (x,y,z).  So to create the sub-assemblies I did a  "copy" to the clip board and then placed the clip board contents into a new file and saved that file.


GadgetAngel's Voron 2.4 Fusion 360 CAD model (.f3d) and (.STEP) files:

The full model for QUEEN has a fusion 360 (.f3d) file and STEP file.  The STEP file for the full model has been integrated by myself from all the sub-assemblies STEP files. This way I could check the sub-assembly files to ensure that they were created correctly.

1.  [QUEEN's Voron 2.4 Fusion 360 model and STEP version](./CAD/QUEEN_Voron_2.4_Build_ZIP_files)

2.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Electronics from the Bottom Electronics Case](./CAD/Electronics_forBottom_Electronic_Case/ZIP_files)

3.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for Electronics from the LitterBox Case](./CAD/Electronics_forLitterBox_Case/ZIP_files)

4.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the LEDs](./CAD/LEDs/ZIP_files)

5.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for all Panels & Clips](./CAD/Panel_Mounting/QUEENv98_SubAssmbly_Panel&Clips_ZIP_files)

6.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for different panels, see this directory for additional sub-assemblies](./CAD/Panel_Mounting)

7. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for all Skirts](./CAD/Skirts/QUEENv98_SubAssmbly_ALL_Skirts_ZIP_files)

8. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for different Skirts (i.e., Front Skirt, Left-Side Skirt, etc.), see this directory for additional sub-assemblies](./CAD/Skirts)

9. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for all the mods located under the Heated Bed & a Filament Runout Sensor](./CAD/Under_Heated_Bed/ZIP_files)

10. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for my Z Driver Tensioner Mod](./CAD/Z_Drive/ZIP_files)

11. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Exhaust Filter](./CAD/Exhaust_Filter/ZIP_files)

12.  [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Frame](./CAD/Frame/ZIP_files)

13. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Gantry](./CAD/Gantry/ZIP_files)

14. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Litter Box Mod and its sub-assemblies, see this directory for additional sub-assemblies](./CAD/Litter_Box_CAD)

15. [QUEEN's Voron 2.4 Fusion 360 subAssembly model (.f3d) and .STEP versions for the Z-Endstop called the "SexBolt Z-Endstop"](./CAD/Z_Endstop/ZIP_files)

16. [QUEEN's Voron 24 Fusion 360 subAssembly model (.f3d) and .STEP version for the BTT piTFT V2.0 articulating arm with display mount](./CAD/Skirts/Front/Middle/ZIP_files)

---

### ".STL List" of files needed for each MOD:

I will be publishing a folder of .stl files for all the printed parts I am using for my QUEEN build, including the ones from my PIF parts ~~(comming soon)~~.

My intent is to list the files needed in each Sub-Assembly and indicate which ".stl files" need to be replaced or exchanged for a MODed ".stl" file.  I think an EXCEL spreadsheet would help with this task and can be found [here](/The_.STL_Files/Excel_Spreadsheet_.stl_files).

The ".STL" files for my QUEEN Voron 2.4 build can be found [here](./The_.STL_Files/Copy_of_.STLs_forQUEEN_As_Built_will-not-be-updated)

---

### Voron 2.4 MODS I plan on using for my Build (250 mm³ Build):


Tool head PCB board (MOD) I am using:

1. [Hartk1213's "Voron Afterburner Toolhead Board v3.rabbit (also known as ERCF PCB board)"](https://github.com/VoronDesign/Voron-Hardware/tree/master/Afterburner_Toolhead_PCB).

    * [Buy Hartk1213's ERCF PCB board at deepfriedhero.in website](https://deepfriedhero.in/products/voron-afterburner-toolhead-board-v3-rabbit?_pos=1&_psq=v3.&_ss=e&_v=1.0)

    * [Wiring Diagram for "Voron Afterburner Toolhead Board v3.rabbit"](https://github.com/VoronDesign/Voron-Hardware/blob/master/Afterburner_Toolhead_PCB/Images/Wiring/ERCF-Toolhead%20SKR%201_4%20wiring.png)

    * Also see my [wiring harness diagram!](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg)

---

Other MODS I am using for my QUEEN build (Z belts 9mm; XY belts 6mm):

1. [Arkeet's "MGN12 Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/arkeet/mgn12);

2. [Hartk1213's "PINS Mod"](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Pins_Mod);

3. [Ramalama2's "Misumi_RBPB5 Mod"](https://github.com/Ramalama2/Voron-2-Mods/tree/main/Misumi_RBPB5);
Note: this replaces the GE5C Mod;

4. [0ndsk4's "NeverMore Micro Filter Mod"](https://github.com/nevermore3d/Nevermore_Micro);

5.  I combined two mods into one, "Z Drive Motor Tensioner Mod" was combined from the following sources:

    * Z Motor A/B Unit combined from [Edwardyeeks' "V2.4_z_drive_motor_tensioner_mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/V2.4_z_drive_motor_tensioner_mod); with my modification for the front Skirts for switches and Hour counter;

    * Z Motor A/B  Motor Unit combined from [Spaghetti-Bolognese's "Z Driver System Mods"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Spaghetti-Bolognese/Z_drive_motor_mount);

6. [Jlas1's "Klicky Probe Mod"](https://github.com/jlas1/Klicky-Probe) and information about the Klicky Probe mod from  [Ramalama2's "KlickyShare GitHub repo"](https://github.com/Ramalama2/Voron-2-Mods/tree/main/KlickyShare);  I also used the following "user mods" for the "Klicky Probe Mod":

    *   ~~[bluedragonx's "BlueDragonX's Klicky Mods" ](using built-in Klicky Probe to X-Axis Carriage Frame): https://github.com/jlas1/Klicky-Probe/tree/main/Printers/Voron/v1.8_v2.4_Legacy_Trident/Usermods/bluedragonx;~~

     Bluedragonx's user mod changes the X-Axis Carriage Frame pieces to allow for a built-in Klicky Probe. I decided to use the regular Klicky Probe mode and a combination of the following two user mods for the Klick Probe body (this way the Klicky Probe is **not** built into the X-Axis Carriage and I can decide to use the Euclid Probe if I so desire [See item #47](#47-derpimus-euclide_probes-omronrotatedxraildock_v2):

    *   [StefanRaatz's Klicky Mods](https://github.com/jlas1/Klicky-Probe/tree/main/Printers/Voron/v1.8_v2.4_Legacy_Trident/Usermods/StefanRaatz);

    *   [Oc_geek's More Roboust Klicky Probe Mod](https://github.com/jlas1/Klicky-Probe/tree/main/Printers/Voron/v1.8_v2.4_Legacy_Trident/Usermods/oc_geek);

7. [Whoppingpochard's "Ti Backers Mod"](https://github.com/tanaes/whopping_Voron_mods/tree/main/extrusion_backers); Y backers 30mm from front; X backer 35mm from the Y axis drag chain;

8. [Ramalama2's "Front_Idlers mod" ](https://github.com/Ramalama2/Voron-2-Mods/tree/main/Front_Idlers); - these are replacement for Phalanx's "Other-V2-Idlers mod;

    * Here is the information on Phalanx's "Other-V2-Idlers mod" if you are interested.  [Phalanx's "Other-V2-Idlers mod"](https://github.com/VoronDesign/VoronUsers/tree/a425971f2986578e2e5c10e638f59d02172687c1/printer_mods/Phalanx/Other-V2-Idlers);


~~9. [Badnoob's "AB-BN30 Afterburner mod"](https://github.com/VoronDesign/VoronUsers/blob/master/printer_mods/Badnoob/AB-BN/Readme.md);~~ I will be using the Stealthburner Mod instead. [Please see item #48](#48-voron-design-teams-stealthburner-mod)

####     10.	[Hartk1213's "Sexbolt Z-Endstop Mod"](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_SexBolt_ZEndstop);

11.	Cover for Toolhead, I created my own (in this repository) - from [Hartk1213's "ERCF covers for the LGX extruder"](https://github.com/VoronDesign/Voron-Hardware/tree/master/Afterburner_Toolhead_PCB/STLs/LGX); I cut the front of the LGX cover for ERCF cover for Stealthburner. See also [Th3fallen's website for the LGX_PCB_Mount_Heatset.stl file](https://github.com/th3fallen/Voron-Hardware/tree/feature/add-heatset-lgx-pcb-mount/Afterburner_Toolhead_PCB/STLs/LGX);

12.	[Whoppingpochard's "Z_Drive_Belt_Exit_Covers Mod"](https://github.com/tanaes/whopping_Voron_mods/tree/main/Z_belt_cable_cover);

13.	[Edwardyeeks' "Decontaminator_Purge_Bucket_&_Nozzle_Scrubber Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/edwardyeeks/Decontaminator_Purge_Bucket_%26_Nozzle_Scrubber);

14.	[Hernsl's "Bottom_panel_mag_clip Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/hernsl/bottom_panel_mag_clip);

15.	[Wile-e1's "Deck_Panel_Support_Clips Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/wile-e1/Deck_Panel_Support_Clips);

16.	[Tayto-chip's "Skirt_switch_mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/tayto-chip/skirt_switch_mod) - with my modifications;

17.	[Leandromarceddu's "PowerSkirt Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/leandromarceddu/PowerSkirt) - with my Modifications;

18.	[StvPtrsn's "Side_Fan_Support_No_Tape Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/StvPtrsn/Side_Fan_Support_No_Tape);

19.	[MarcPot's "Skirt_Mod_250 Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/MarcPot/Skirt_Mods); - with my modification so that you can use this with the magnatic bottom panel;

20. My BTT-PITFT5-Mount Mod come from the following sources:

    * [Alanho's "BTT_PITFT50_v2_Mount Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/alanho/BTT_PITFT50_v2_Mount);

    * [Smaseface's "BTT-PITFT5-Mount mod"](https://github.com/smaseface/BTT-PITFT5-Mount-for-Voron-v2.4);

    * [Revnull's "Articulating arm" from his "rpi_7in_display_mount mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/revnull/rpi_7in_display_mount);

    * [driftology's "Fysetc Paneldue 7i V3 Voron 2 Adapter on Thingiverse.com"](https://www.thingiverse.com/thing:4571677);

21.	[Randell's "Microswitch_Endstop POD"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/randell/Microswitch_Endstop);

22. [Ramalama2's "Misumi_Cable_Clip mod"](https://github.com/Ramalama2/Voron-2-Mods/tree/main/Misumi_Cable_Clip);

23. [Ramalama2's "AB_Plug_Microfit mod"](https://github.com/Ramalama2/Voron-2-Mods/tree/main/AB_Plug_Microfit); or [AB_Plug_JST-XHmod](https://github.com/Ramalama2/Voron-2-Mods/tree/main/AB_Plug_JST-XH); or you could also use the Voron Design Team's ["Tie-down the AB motors cables to the Z-Beam Mod"](https://github.com/VoronDesign/Voron-2/blob/Voron2.2/STLs/VORON2.2/Gantry/%5Ba%5D_cable_anchor_x4_rev1.stl);

#####       24.  [Ramalama2's "Panel_Clips"; I will use the midspan clips for sides and top](https://github.com/Ramalama2/Voron-2-Mods/tree/main/Panel_Clips); - (use 6mm version - 3mm panel and 3mm of foam tape);

25. [Richardjm's "ADXL345 Mount Mod"](https://github.com/richardjm/VoronUsers/tree/richardjm/adxl-chain/printer_mods/richardjm/adxl-chain); I used information from [Padok's ADXL345 Mount](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/padok/chain_anchor-ADXL345_mount);

26. [Eddie's "LED_Bar_Clip mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/eddie/LED_Bar_Clip);

27. [Hartk1213's  "AB Spinner (Voron2.4_Spinner) mod"](https://github.com/hartk1213/MISC/tree/main/Voron%20Mods/Voron%202/2.4/Voron2.4_Spinner); or [Rubber Ducky Spinner Mod](https://discord.com/channels/460117602945990666/828406858271162378/875463215721644032)

28. [42bios' "corner_panel_clip_cable mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/42bios/corner_panel_clip_cable); Also my own modification for these clips so I can use them to mount the Mikro10 Illumination Edge Bracket on the side panels.

29. [OV1A's "WAGO+221+DIN+rail+holder mod" from Thiniverse.com](https://www.thingiverse.com/thing:4972435); Used to mount the WAGO nuts on the DIN rails.

30. [The0bone's "Voron 2.4 China Chain Guide mod" on Prusaprinters.org](https://www.prusaprinters.org/prints/69683-voron-24-china-chain-guide?fbclid=IwAR1xfiLFqM1xiLLYC27wswsilp6afWQkuD313DK3K7LC2ITIk452Heg-T0U);

31. For handling the thermal expansion on the Build Plate for QUEEN, I added the Mandala Rose Works's ["Matched Height Kinematic Kit"](https://www.mandalaroseworks.com/shop/voron/matched-height-kinematic-kit) along with ["Voron 250 Standard Bed"](https://www.mandalaroseworks.com/shop/voron/voron-250-standard-bed),

    The following will be needed if you add the kinematic kit to your Voron 2.4 Build:
    *  [Modified Purge Bucket](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/tree/main/The_.STL_Files/GA_modded_STLs/Decontaminator_Purge_Bucket_%26_Nozzle_Scrubber_MOD);
    *  [buy a longer sexbolt for](https://www.amazon.com/gp/product/B07GSQZWNP) [Item #10](#10hartk1213s-sexbolt-z-endstop-mod) and
    *  buy some [Openbuild's Angled brackets](https://deepfriedhero.in/products/openbuilds-angle-corner-connector?_pos=2&_sid=c4c7e2ca4&_ss=r) or you could just use blind joints;

32. [GadgetAngel's "Litter Box mod"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/tree/main/Electronics_Case_Wiring_Diagram/Litter_Box_Mod);

33. I also used all [Trident DIN clips](https://github.com/VoronDesign/Voron-Trident/tree/main/STLs/ElectronicsBay) for mounting electronics and I used [Trident 3D Printed Parts on the MGN12 Mod](https://github.com/VoronDesign/Voron-Trident/tree/main/STLs/Gantry/X_Axis/X_Carriage). **Thank you Voron Design Team for all your hard work!**

34. [Nemgrea & Geoffreyyoung's "LGX Extruder Mod to replace the Clockwork extruder"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/geoffreyyoung/lgx);

35. [LoCoCNC's "Wire_grommets"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/LoCoCNC/wire_grommets); modified for Kinematic Bed;

36. [Danowar's "Humidity_Sensor_Bracket"](https://github.com/VoronDesign/VoronUsers/tree/master/legacy_printers/printer_mods/Danowar/Humidity_Sensor_Bracket);

37. [Mikro10 Illumination Edge Bracket for the Side panels](https://www.wired4signsusa.com/products/edge-lit-led-extrusion-for-1-4-acrylic-mikro10?adg_id=87314711028&cmp_id=6613373433&device=c&gclid=Cj0KCQjwub-HBhCyARIsAPctr7zbuecNIcr3v6Q-rKfdWc7mU8h6LHWWi03DaAadUDBfhbv_PXq73eEaApGcEALw_wcB&hsa_acc=4180687217&hsa_ad=386204908692&hsa_cam=6613373433&hsa_grp=87314711028&hsa_kw=&hsa_mt=&hsa_net=adwords&hsa_src=u&hsa_tgt=pla-293946777986&hsa_ver=3&kwd=&utm_campaign=Shopping%20Campaign&utm_content=sag_organic&utm_medium=ppc&utm_source=adwords&utm_term=&variant=32250290143298); I modified [42bios' "corner_panel_clip_cable mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/42bios/corner_panel_clip_cable) so I could mount the Mikro10 illumination edge bracket to light the side panels.

38. [Boingomw's "Wago_mount mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Boingomw/Wago_mount) used for Wago mount near the Build Plate;

39. [GSL12's "wago_221_mount mod"](https://github.com/VoronDesign/VoronUsers/tree/master/legacy_printers/printer_mods/GSL12/wago_221_mount); Used these to place WAGO nuts around the whole Voron 2.4 printer mounted to the extrusions.

40. [Jeoje's "Molex_MLX_Microfit_Bed_Connector_Mount Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/jeoje/Molex_MLX_Microfit_Bed_Connector_Mount);

41. [Richardjm's "Back plate blanking plate mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/richardjm/back-plate);

42. [Jeoje's "Z_Chain_Guide_Thermistor_Mount mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/jeoje/Z_Chain_Guide_Thermistor_Mount);

43. [BladeScraper-Designs' "Horizontal-Spool-Holder Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/BladeScraper-Designs/Horizontal-Spool-Holder);

44. [Empusas' "BTT_Filament_Motion_Sensor_Mount Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Empusas/BTT_Filament_Motion_Sensor_Mount);

45. [Ellis' "Bed_Fans Mod"](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Ellis/Bed_Fans);

46. [Ramalama2's "Misumi_Led_Corners"](https://github.com/Ramalama2/Voron-2-Mods/tree/main/Misumi_Led_Corners);

#####     47. [Derpimus' Euclide_Probe's "OmronRotatedXRailDock_v2"](https://discord.com/channels/460117602945990666/916406093339566120/923047248051462226);

#####     48. [Voron Design Team's "Stealthburner Mod"](https://github.com/VoronDesign/Voron-Afterburner/tree/sb-beta/STLs);

49. [Voron Desing Team's "Z Rail end stops"](https://github.com/VoronDesign/Voron-2/blob/Voron2.2/STLs/VORON2.2/Gantry/%5Ba%5D_z_rail_stop_x4_rev1.stl);

50. [AlexanderT-Moss's 270-Clamping-Hinges for the front doors](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/AlexanderT-Moss/270-Clamping-Hinges) [instead of Item #24's Front door clips](#24--ramalama2s-panel_clips-i-will-use-the-midspan-clips-for-sides-and-top---use-6mm-version---3mm-panel-and-3mm-of-foam-tape);

51. [AlchemyEngine's Skirt-Microfit-Inserts](https://github.com/alchemyEngine/EnragedRabbitProject/tree/main/usermods/Skirt-Microfit-Inserts) - I modified it so I could mount a Reset button for the BTT V1.2 Relays shown on my AC Wiring Diagram;

52. [V6cl's Lift Handles](https://github.com/v6cl/My-Voron2.4-Customs/tree/main/LiftHandle) - I modified the Lift Handles so they will fit my Side panels which have Edge lighting.  Instead of 7 mm clearence I will need 11 mm cleareance.

53. [V6cl's Panel_Locker](https://github.com/v6cl/My-Voron2.4-Customs/tree/main/Panel_Locker) as the front door handles.

If you are looking for 3D CAD models for the different Voron Build plates you can find them at https://github.com/lecktor/Voron-V2.4

I created a 3D CAD model for the Mandala Rose Works's MIC6 Build plate for the 250mm build. You can find it at https://github.com/GadgetAngel/Voron2.4_My_Build_Log/tree/main/CAD/Under_Heated_Bed.

## How I Calculated the Power Requirements for my Voron 2.4 Build:

I know a lot of you already know the answer but for the rest of us that are still learning about bipolar stepper motors and stepper drivers I will describe the process I used.  I never realized that the motors I own are **bipolar-series motors**.

To me when things are connected in series the wires are daisy-chained together (positive lead1, negative lead1 is connected to positive lead2, negative lead2).

When things are wired in parallel then the positive leads are connected together and the negative leads are connected together.

So I thought the 3D printer motors where connected together in parallel on the 3D printer, which they are. If you look at the **system in a "macro" view** not a "micro" view.

My problem was not understanding the term "series" and "parallel" when it applies to the internal wiring of the 4-wire bipolar motor (a "micro" view).

I had to look at an 8-wire bipolar motor before I actually got it through my thick head.

Maybe this will help others:

[Drawing of 8 wire bipolar-parallel motor](https://www.google.com/imgres?imgurl=https://buildbotics.com/content/images/2019/09/8wireParallel.png&imgrefurl=https://buildbotics.com/wiring-stepper-motors/&tbnid=HgNwYdr3N6uCPM&vet=1&docid=NKxfcF59LDIYkM&w=735&h=411&source=sh/x/im)

[Drawing of 8 wire bipolar-series motor](https://www.google.com/imgres?imgurl=https%3A%2F%2Fbuildbotics.com%2Fcontent%2Fimages%2F2019%2F09%2F8wireSeries.png&imgrefurl=https%3A%2F%2Fbuildbotics.com%2Fwiring-stepper-motors%2F&tbnid=c1vZXhJLkcsohM&vet=12ahUKEwinr7uN1aXzAhUGFKwKHYYtChEQMygJegUIARCzAg..i&docid=NKxfcF59LDIYkM&w=716&h=395&q=stepper%20driver%20schematic%20with%20bipolar%20motor%20series&ved=2ahUKEwinr7uN1aXzAhUGFKwKHYYtChEQMygJegUIARCzAg)

So ALL my motors are 4-wire bipolar-series motors!

 To Determine the amount of Power Required for your Voron 2.4 build:

 Fact: During a Z Hope move 6 motors will be active at a time.

 Fact:  Extruder (E) Motor LDO-42STH20-1004ASH:
		Rated Peak current: 1.0A/ Phase

 Fact:  Z motors and AB motors are LD0-42STH40-2004MAH
		Rated Peak current: 2.0A / Phase

 Rule of Thumb (https://robotics.stackexchange.com/questions/14071/how-to-calculate-my-power-supply-voltage-and-current):

 1. Power_supply_current = number_of_motors * 1/3 * motor_peak_current for "bipolar-series motors" (All LDO motors are bipolar-Series Motors!)

 2. Power_supply_current = number_of_motors * 2/3 * motor_peak_current for "bipolar-parallel motors"

 Since ALL LDO motors I own are bipolar-Series Motors we will use Rule of Thumb #1 ONLY!

 Power_ supply_current = (5 * 1/3 * 2.0 Amps) + (1 * 1/3 * 1.0A) = 3.333 + 0.333 = 3.6667 or 4 Amps.

 So for **my bipolar-series motors** I want to know many Watts of power is 4 Amps at 48 VDC?

 Answer: Watts = Volts * Amps

 So, 48VDC * 4 Amp = 192 Watts or 200 Watts PSU (if the PSU supplies the full power without an aluminum plate for heat dissipation [PSU's Derating Curve]).

Options for powering my Voron 2.4 printer at 48 VDC, and 24 VDC (running all HT motors from LDO at 48VDC) with the following:

See UHP-200 Spec Data sheet : https://www.meanwellusa.com/upload/pdf/UHP-200(R)/UHP-200-spec.pdf

See UHP-350 Spec Data sheet : https://www.meanwellusa.com/upload/pdf/UHP-350(R)/UHP-350-spec.pdf

See UHP-500 Spec Data sheet : https://www.meanwellusa.com/upload/pdf/UHP-500(R)/UHP-500-spec.pdf

If you are having a hard time finding UHP-xxx series of power supplies, there are two names for these UHP supplies.  One name is UHP-350-24, UHP-350-48 and so on. While the other name is UHP-350R-24, UHP-350R-48 and so on.  The extra "R" in the model number just indicates that you have the option of wiring 2 power supplies in parallel.  The "R" version will work if you can not find the regular version to buy.

---

1. 48V PSU UHP-200-48 (AC to DC PSU)[(4.2A*0.8)= 3.36 Amps; I need 4 Amps! [without an aluminum plate, so 80%]] : https://www.digikey.com/en/products/detail/mean-well-usa-inc/UHP-200-48/7707242

2. 24V PSU UHP-200-24 (AC to DC PSU)[(8.4A*0.8)= 6.72 Amps ; I want at least 9 Amps! [without an aluminum plate, so 80%]]: https://www.digikey.com/en/products/detail/mean-well-usa-inc/UHP-200-24/7707239

---

3. 48V PSU UHP-350R-48 (AC to DC PSU)[(7.3A*0.70)= 5.32 Amps; I need 4 Amps [without an aluminum plate, so 70%]] : https://www.digikey.com/en/products/detail/mean-well-usa-inc/UHP-350-48/7707258; https://www.newark.com/mean-well/uhp-350r-48/power-supply-ac-dc-48v-7-3a/dp/01AH8032?ost=uhp-350r-48

4. 24 PSU UHP-350R-24 [(14.6A*0.70)= 10.22 Amps; I want at least 9 Amps [without an aluminum plate, so 70%]]: https://www.digikey.com/en/products/detail/mean-well-usa-inc/UHP-350-24/7707254;
https://www.newark.com/mean-well/uhp-350r-24/power-supply-ac-dc-24v-14-6a/dp/01AH8029?ost=uhp-350r-24

---

5. 48V PSU UHP-500-48 (AC to DC PSU)[(10.45*0.7)= 7.315 Amps; I need 4 Amps [without an aluminum plate, so 70%]] : https://www.digikey.com/en/products/detail/mean-well-usa-inc/UHP-500-48/8324039;
https://www.newark.com/mean-well/uhp-500-48/power-supply-ac-dc-48v-10-45a/dp/01AH8038?ost=uhp-500-48

6. 24V PSU UHP-500-24 (AC to DC PSU)[(20.9*0.7) = 14.63 Amps; I want at least 9 Amps [without an aluminum plate, so 70%]]: https://www.digikey.com/en/products/detail/mean-well-usa-inc/UHP-500-24/8324036; https://www.newark.com/mean-well/uhp-500-24/power-supply-ac-dc-24v-20-9a/dp/01AH8036?ost=uhp-500-24

---

So I could use option 3 & 4 **OR** 5 & 6.

Since I plan on LEDS; running a Raspberry Pi 4B with a solid state disk drive (via USB 3.1 interface instead of using a Micro-SD card); and a camera, I want to have enough power to add extras to the Voron Build.

I opted to buy the following:

    A. UHP-500-48 for my 48VDC supply
    B. UHP-500-24 for my 24VDC supply
    C. RS-25-5 for my 5VDC supply
    D. UHP-200-12 for my 12VDC supply.

I will use the Octopus Pro to power the stepper motor drivers, heater cartridge, temperature sensors, limit switches, and generate signals on PINs to control stuff, but I do not plan on powering stuff off the Octopus Pro board that is considered optional equipment like LEDs, and endoscope or cameras.  Since my Raspberry Pi (running Klipper) is the brains of this setup, I will be using a solid state drive to act as the disk drive for the Raspberry Pi.  This adds additional current draw and the Raspberry Pi will have its own 5V PSU.

All my LEDS are 12VDC or 24VDC. So that is why I am running a separate 12VDC PSU and added additional current capability to my 24VDC supply.

I plan on running all TMC5160 (HV) PRO stepper motor drivers for all my motors on QUEEN.
I know this is an overkill but if I want the power it will be there. I am lazy, and I do not want to redo wiring at a later date.

~~I am hoping I can fit all of this in my electronics case for a 250 mm build.~~ Edited: There is not enough room for all the PSU and all the electronics therefore I developed my own "Litter Box" Mod so I can keep the AC Power in the bottom electronic's case and use my "Litter Box" for the DC electronic components.

I explain the "Litter Box" Mod at https://github.com/GadgetAngel/Voron2.4_My_Build_Log/tree/main/Electronics_Case_Wiring_Diagram/Litter_Box_Mod

1/5/2022:  Click [here](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/tree/main/Electronics_Case_Wiring_Diagram#lesson-learned-while-doing-the-electronics-case-wiring-diagram-for-queen) to see additional discussion about the Voron 2.4 AC wiring diagram.

Click here see the JPG file for the ["Voron 2.4 AC Electrical Wiring Diagram"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/tree/main/Electronics_Case_Wiring_Diagram#a-picture-of-the-voron-24-ac-electrical-wiring-diagram-for-queen)

To download the PDF just click on the filename ["Voron_2.4_Electronics_Case_Wiring_Diagram_AC_wiring.pdf"](images/Voron_2.4_Electronics_Case_Wiring_Diagram_AC_wiring.pdf) and hit the download button.


## The PDF file of the "Color PIN Diagram" for the Octopus Pro V1.0:

You can view the PDF in your browser by clicking on the filename ["BIGTREETECH-Octopus-Pro-V1.0-Color-PIN-V3.0.pdf"](https://github.com/GadgetAngel/BTT_Octopus_Color_PIN_Diagram/blob/main/BTT_Octopus_Pro_V1.0_Color_PIN_Diagram/BIGTREETECH-Octopus-Pro-V1.0-Color-PIN-V3.0.pdf) and then hit the download button.

You can view an even higher resolution image (give it a minute or two to load, it takes longer due to the higher resolution) when you view the PDF in your browser by clicking on the filename ["BIGTREETECH-Octopus-Pro-V1.0-Color-PIN-V3.0-400ppi.pdf"](https://github.com/GadgetAngel/BTT_Octopus_Color_PIN_Diagram/blob/main/BTT_Octopus_Pro_V1.0_Color_PIN_Diagram/BIGTREETECH-Octopus-Pro-V1.0-Color-PIN-V3.0-400ppi.pdf) and then hit the download button.

## A Picture of the "Color PIN Diagram" for the Octopus Pro V1.0:

You can download the JPG file for this "Color PIN Diagram" by clicking on the filename ["BIGTREETECH-Octopus-Pro-V1.0-color-PIN-V3.0.jpg"](https://github.com/GadgetAngel/BTT_Octopus_Color_PIN_Diagram/blob/main/BTT_Octopus_Pro_V1.0_Color_PIN_Diagram/BIGTREETECH-Octopus-Pro-V1.0-color-PIN-V3.0.jpg) or the filename ["BIGTREETECH-Octopus-Pro-V1.0-color-PIN-V3.0-400ppi.jpg"](https://github.com/GadgetAngel/BTT_Octopus_Color_PIN_Diagram/blob/main/BTT_Octopus_Pro_V1.0_Color_PIN_Diagram/BIGTREETECH-Octopus-Pro-V1.0-color-PIN-V3.0-400ppi.jpg) and then hit the download button.

Again, to download the PDF just click on the filename ["BIGTREETECH-Octopus-Pro-V1.0-Color-PIN-V3.0.pdf"](https://github.com/GadgetAngel/BTT_Octopus_Color_PIN_Diagram/blob/main/BTT_Octopus_Pro_V1.0_Color_PIN_Diagram/BIGTREETECH-Octopus-Pro-V1.0-Color-PIN-V3.0.pdf) or the filename ["BIGTREETECH-Octopus-Pro-V1.0-Color-PIN-V3.0-400ppi.pdf"](https://github.com/GadgetAngel/BTT_Octopus_Color_PIN_Diagram/blob/main/BTT_Octopus_Pro_V1.0_Color_PIN_Diagram/BIGTREETECH-Octopus-Pro-V1.0-Color-PIN-V3.0-400ppi.pdf) and hit the download button.

![JPG of Color PIN Diagram](images/BIGTREETECH-Octopus-Pro-V1.0-color-PIN-V3.0.jpg)

## "Wiring_Harness_Diagram" for QUEEN:

This is the wiring harness diagram I developed for my Voron 2.4 build, it is also in the directory called "Wiring_Harness_Diagram".

Please take notice of the "Notes" section on the "Wiring_Harness_Diagram".

To ensure you see it, I am going to repeat it here:

```
Note about the Hartk1213 v3.rabbit board:
If the jumper pads on the back of the v3.rabbit are configured
incorrectly you could end up damaging your Octopus Pro mother board!!

Because there are two different versions of this Toolhead board around (let’s call them version #1,
and version #2), before powering on your printer, please ensure that the jumper pads on the back of
the v3.rabbit Toolhead board are properly configure for your FANS and ABL!

How to tell which version of the v3.rabbit Toolhead board you own:

If you turn the board over on its back, you will see a bank of jumper pads.  For version #1 of the
v3.rabbit Toolhead board has 4 columns by 3 rows of jumper pads.  For version #2 of v3.rabbit
Toolhead board has 3 columns by 3 rows of jumper pads.  If you have version #1 of the v3.rabbit
Toolhead board (4 columns by 3 rows of jumper pads) than you are responsible for bridging the
jumper pads to your desired voltage (in my case I would solder a bridge to 24VDC for ABL, PCF, HEF,
and FS).  If you have version #2 of the v3.rabbit Toolhead board (3 columns by 3 rows of jumper
pads) than all the selectable voltages default to 24VDC!

Here is what the labels mean:
ABL means auto bed leveling or an inductive probe or the proximity sensor connector;  PCF means
Part Cooling Fan; HEF means Hotend Fan; and FS means Filament Switch Sensor.

For version #1 of the v3.rabbit board, the columns are labeled from left to right: ABL, PCF, HEF,
FS. For version #2 of the v3.rabbit board, the columns are labeled from left to right: ABL, PCF,
HEF.

For version #1 and version #2 the rows are: 1st row is 24VDC; 2nd row is (ABL, PCF, or HEF, {only
on Version #1 FS}); and 3rd row is 5VDC.

If you have version #2 and you want 5VDC, you are going to cut the trace to the 24VDC on the
desired PIN (ABL, PCF or HEF)!
```

![JPG of wiring harness Diagram](images/Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg)

You can download the JPG file for this "Wiring_Harness_Diagram" by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg).

 You can view an even higher resolution image (give it a minute or two to load, it takes longer due to the higher resolution) when you view the JPG in your browser by clicking on the filename  ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg) and then hit the download button.

## PDF version of the for Wiring_Harness_Diagram":

You can view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) and then hit the download button.

You can view an even higher resolution image (give it a minute or two to load, it takes longer due to the higher resolution) when you view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and then hit the download button.

## "Electronics_Case_Wiring_Diagram" directory you will find the wiring diagram for the electronics case for QUEEN:

Click here see the JPG file for the ["Voron 2.4 AC Electrical Wiring Diagram"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/tree/main/Electronics_Case_Wiring_Diagram#a-picture-of-the-voron-24-ac-electrical-wiring-diagram-for-queen)

To download the PDF just click on the filename ["Voron_2.4_Electronics_Case_Wiring_Diagram_AC_wiring.pdf"](images/Voron_2.4_Electronics_Case_Wiring_Diagram_AC_wiring.pdf) and hit the download button.


## How Well Will Your Motors Perform on a Voron Build?

You need to look at the torque curve for your motors and see how your motors perform at different voltages.

Here is an Excel spreadsheet that can help you: https://github.com/eddietheengineer/documentation/tree/master/stepper_motor/data

To download the spreadsheet, just click on the file named ["motor_torque_sim_v7_database.xlsm"](https://github.com/eddietheengineer/documentation/blob/master/stepper_motor/data/motor_torque_sim_v7_database.xlsm) and hit the download button.

Once the Excel spreadsheet "motor_torque_sim_v7_database.xlsm" has downloaded, open it up in Excel but remember to "Enable" editing. If you do not enable editing you will not be able to see the "torque curve" graph. Also, the motors that are graphed can be chosen from a dropdown list. The voltage you run the stepper motors at can also be entered as can the current level.

Here are examples of Torque Curves produced by the Excel Spreadsheet:

As you will see when you go from 24V to 48V you can move faster. Also notice that when you go from 48V to 60V the gain is smaller than the jump from 24V to 48V!

Here is the Torque Curve for the specified stepper motors at 24 VDC:

![Motor Torque Curve for 24V](images/Motor_Torque_Curve_for_24V.jpg)

Here is the Torque Curve for the same specified stepper motors at 48 VDC:

![Motor Torque Curve for 48V](images/Motor_Torque_Curve_for_48V.jpg)

Here is the Torque Curve for the same specified stepper motors at 60 VDC:

![Motor Torque Curve for 60V](images/Motor_Torque_Curve_for_60V.jpg)


As you can see when you go from 24V to 48V you can move faster. Also notice that when you go from 48V to 60V the gain is smaller than the jump from 24V to 48V!

## The Original BIGTREETECH Wiring Diagram for the Octopus Pro V1.0:

![Original Wiring Diagram](images/BIGTREETECH-Octopus-Pro-V1.0-Original-Wiring-Diagram.jpg)

## BIGTREETECH has a GitHub repository for the Octopus Pro V1.0:

The BIGTREETECH GitHub repository for Octopus Pro is located at https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-Pro

## BIGTREETECH has a GitHub repository for the Octopus V1.0/1.1 Board:

The BIGTREETECH GitHub repository for Octopus 1.0/1.1 is located at https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-V1.0

This repository also has information on how to wire up an Octopus V1.0/V1.1 board for a Voron Build and is located at https://github.com/bigtreetech/BIGTREETECH-OCTOPUS-V1.0/tree/master/Octopus%20works%20on%20Voron%20v2.4/Firmware

## Klipper firmware supports the Octopus Pro V1.0 board:

Here is the link to the config file on GitHub for the Octopus pro V1.0 board https://github.com/Klipper3d/klipper/blob/master/config/generic-bigtreetech-octopus.cfg.

If you are using the "PROBE" connector for a proximity sensor you will need to add a [probe] section to the "generic-bigtreetech-octopus.cfg" file and ensure that the sensor_pin: PC5

There is only two PINs that are different between the Octopus V1.1 pin-out and the Octopus Pro V1.0 pin-out. The Octopus V1.1 pin-out has PC5 on the EXP2 connector but on the Octopus Pro V1.0 this pin on the EXP2 connector is now "Not Connected (NC)".

The second PIN difference is that on the Octopus V1.1 pin-out PB7 is the signal PIN used on the PROBE/SENSOR connector and on the BLTouch header but on the Octopus Pro V1.0 the signal pin on the PROBE connector is PC5.  Which means that on the Octopus V1.1 board you can only use either a BLTouch or a Proximity Sensor but NOT both. On the Octopus Pro V1.0 since the signal pins for the PROBE connector is different from the BLTouch, if you wanted to, you could use both ports.

If you plan to use a voltage higher than 24V on MOTOR_POWER_IN then please pay attention to the footnote #1 on the "Color PIN Diagram".

You may need to change the Fuse on the MB_POWER_IN. To calculate the maximum amps you will be using on the MB_POWER_IN connection you will need to know the maximum amps allowed on the 24VDC rail for the motherboard.

To calculate the maximum amps allowed on the 24VDC rail on mother board:

 (the four heaters {HE0-HE3}, 3.3VDC rail, 5VDC rail, and 12VDC rail are all produced from the 24VDC rail).

 The maximum amps for 3.3VDC rail is 1 Amp.

 The maximum amps for the 5VDC rail is 8 Amps.

 The maximum amps for 12VDC rail is 4 Amps.

 So the total maximum amps for 3.3VDC rail + 5VDC rail + 12VDC rail is equal to 13 Amps, but the amps needed to run the four heaters needs to be added to this value.

 Since BIGTREETECH supplies us with a 20 Amp fuse, then BIGTREETECH is saying that you have 7 more Amps available for all four heater ports or 1.75 Amps / heater cartridge. Just do not use more than 7 Amps on any combination of the four heater {HE0-HE3} ports!

Please use the "Color PIN Diagram" in [BTT_Octopus_Pro_V1.0_Color_PIN_Diagram](https://github.com/GadgetAngel/BTT_Octopus_Color_PIN_Diagram/tree/main/BTT_Octopus_Pro_V1.0_Color_PIN_Diagram) to obtain the correct PIN assignments.

If you decide to flash a new bootloader to the Octopus Pro V1.0 board (you should not need to because you can upload the new Klipper firmware using the micro-SD card reader) and find that the micro-SD card bootloader no longer works you will want to return the board to its shipment state by finding the original bootloader and "bootlaoder+firmware" files at https://github.com/GadgetAngel/BTT_SKR_13_14_14T_SD-DFU-Bootloader/tree/main/bootloader_bin/backed_up_original_bootloaders

