# HOW TO PROGRAM THE 6X6X6 CUBE WITH ARDUINO

1.       Download the STM32 libraries from  https://github.com/rogerclarkmelbourne/Arduino_STM32

2.        Download Arduino 1.6.5 from here( suggest version 1.6.5, it's tested and confirmed working on Win amd MAC, haven't test other version) https://www.arduino.cc/en/Main/OldSoftwareReleases#previous

3.       Change the folder name Arduino_STM32 to STM32, and then put the folder to ~\arduino-1.6.5-r5-windows\arduino-1.6.5-r5\hardware

4.        Run the Arduino IDE, on the Tools menu, select the Boards manager, and install the Arduino SAM Boards (32-bits for ARM Cortex-M3).

5. 	  Unzip L3D_CubePixel.zip and beta-cube-library.zip and put these two libraries under arduino library folder  ..\..\arduino-1.6.5-r5-windows\arduino-1.6.5-r5\libraries

6.        Restart Arduino IDE, then select Maple (Rev3) for programming.

**Enclosed a Demo for reference, enjoy it!
