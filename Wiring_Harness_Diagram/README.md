# This repositoy uses LFS extension

```
I use Git for Windows with VScode to manage this repository.  I also use Git LFS extensions
for .pdf and .png files.

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
## This repository can be downloaded as one large zip file from my Google drive at:

xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx

# Wiring Harness for QUEEN (my Voron 2.4 build):

This repository contains JPG and PDF files for the wiring harness for QUEEN.

### The PDF file of the "Wiring Harness" for QUEEN:

The PDF file looks the same as the JPG file. You can enlarge the image for both file types to get all the details.

You can view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) and then hit the download button.

You can view an even higher resolution image (give it a minute or two to load, it takes longer due to the higher resolution) when you view the PDF in your browser by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and then hit the download button.

## A Picture of the "Wiring Harness" for QUEEN:

This is the wiring harness diagram I developed for my Voron 2.4 build:

You can download the JPG file for this "Wiring_Harness_Diagram" by clicking on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg).

 You can view an even higher resolution image (give it a minute or two to load, it takes longer due to the higher resolution) when you view the JPG in your browser by clicking on the filename  ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.jpg) and then hit the download button.


Again, to download the PDF just click on the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness.pdf) or the filename ["Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf"](https://github.com/GadgetAngel/Voron2.4_My_Build_Log/blob/main/Wiring_Harness_Diagram/Voron_2.4_Tool_Head_PCB__Wiring_Harness_400ppi.pdf) and hit the download button.

Please take notice of the Notes on the "Wiring_Harness_Diagram".  To ensure you see it, I am going to repeat it here:

Note about the Hartk1213 v3.rabbit board:
If the jumper pads on the back of the v3.rabbit are configured
incorrectly you could end up damaging your Octopus Pro mother board!!

Because there are two different versions of this Toolhead board around (let’s call them version #1, and version #2), before powering on your printer, please ensure that the jumper pads on the back of the v3.rabbit Toolhead board are properly configure for your FANS and ABL!

How to tell which version of the v3.rabbit Toolhead board you own:

If you turn the board over on its back, you will see a bank of jumper pads.  For version #1 of the v3.rabbit Toolhead board has 4 columns by 3 rows of jumper pads.  For version #2 of v3.rabbit Toolhead board has 3 columns by 3 rows of jumper pads.  If you have version #1 of the v3.rabbit Toolhead board (4 columns by 3 rows of jumper pads) than you are responsible for bridging the jumper pads to your desired voltage (in my case I would solder a bridge to 24VDC for ABL, PCF, HEF, and FS).  If you have version #2 of the v3.rabbit Toolhead board (3 columns by 3 rows of jumper pads) than all the selectable voltages default to 24VDC!

Here is what the labels mean:
ABL means auto bed leveling or an inductive probe or the proximity sensor connector;  PCF means Part Cooling Fan; HEF means Hotend Fan; and FS means Filament Switch Sensor.

For version #1 of the v3.rabbit board, the columns are labeled from left to right: ABL, PCF, HEF, FS. For version #2 of the v3.rabbit board, the columns are labeled from left to right: ABL, PCF, HEF.

For version #1 and version #2 the rows are: 1st row is 24VDC; 2nd row is (ABL, PCF, or HEF, {only on Version #1 FS}); and 3rd row is 5VDC.

If you have version #2 and you want 5VDC, you are going to cut the trace to the 24VDC on the desired PIN (ABL, PCF or HEF)!

![JPG of wiring harness Diagram](Voron_2.4_Tool_Head_PCB__Wiring_Harness.jpg)
