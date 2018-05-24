Hardware low power device to trigger messages when detect earthquakes:

Libraries needed:
Accelerometer library: https://github.com/Flummy/FluMMA865x

All easily modifiable values are in def.h:
- Variable clock fix loop
- Variable device sleep loop
- Variable gravity scale for accelerometer
- Variable accelerometer sensitivity threshold,
- Variable accelerometer sleep count after interrupt
- Variable accelerometer data rate for sleep and wake modes


Steps to flash Hidnseek device:

Short:
1. Take off top
2. Plug device into power source
3. Short G and R pins
4. Quickly upload firmware as programmer (Arduino IDE: Sketch->Upload using programmer)
(Important that step 4 is done quickly after step 3, while red light flashing on device)

Long(First setup):
Follow instructions here: https://github.com/Bucknalla/sigfox-hidnseek-tutorial/blob/master/README.md
