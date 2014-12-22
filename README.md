KreyosFirmware
==============

Build Instruction:

1. The build tool is IAR MSP-430 5.50 (5.51.3 earliest I could find @ http://processors.wiki.ti.com/index.php/IAR_Embedded_Workbench_Kickstart_for_TI_MSP430_Release_Notes)
2. You need a working instance of *make* in path, like . Suggest to install msys/mingw32
3. run make -f Makefile.msp430, a watch.txt will be generated @objs.msp430.
4. *(either)* use tool/convertbin to convert txt file to a bin file that is able to upload through phone application
4. *(or)* use BSL tool in KreyosFirmware/BSL.exe to program over the USB cable 
