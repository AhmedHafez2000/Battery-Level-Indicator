# Battery-Level-Indicator

 The circuit is responsible for indicating the charge level of a battery.
It is designed for 3S battery pack with voltage range from 9V to 12.6V.

It is based on **LM3914 Dot/Bar display driver**

The driver is used in Dot mode, but when the battery is fully charged, it switches to Bar mode and lights all white LEDs. When the battery is too low, the red LEDs light up instead of the white LEDs.

This circuit can be fabricated in home a printable file is attached in PCB folder.

## DIY Sample
![](https://github.com/AhmedHafez2000/Battery-Level-Indicator/blob/main/Photos/IMG_1.jpg?raw=true)
![](https://github.com/AhmedHafez2000/Battery-Level-Indicator/blob/main/Photos/IMG_2.jpg?raw=true)
![](https://github.com/AhmedHafez2000/Battery-Level-Indicator/blob/main/Photos/IMG_3.jpg?raw=true)

LEDs with 0603 footprint used instead of 0805 footprint as it isn't available for now.

## Schematic
![Schematic](https://github.com/AhmedHafez2000/Battery-Level-Indicator/blob/main/Schematic/Battery%20Level%20Indicator-Sch.png?raw=true)

MT3608 boost converter is used to maintin a stable voltage level to make sure that  the calibrated voltages are stable.

and the 2 potentiometer in the schematic are used to calibrate the upper and lower limmits of battery voltage range.

## 2D PCB
![2D PCB](https://github.com/AhmedHafez2000/Battery-Level-Indicator/blob/main/PCB/2D-Top.png?raw=true)
**NOTE:** The bottom connection are jumper wires.

## 3D PCB
![3D PCB](https://github.com/AhmedHafez2000/Battery-Level-Indicator/blob/main/PCB/3D-Top.png?raw=true)