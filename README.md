# Camera-Len-Wireless-Follow-Focus-System
***Learning C++ hardly...***

**[简体中文](https://github.com/ZhongWwwHhh/Camera-Len-Wireless-Follow-Focus-System/blob/main/README_ZH_CN.md)**

## Brief Instructions for Use
If you are an enthusiast and only want to make and use it personally, check this document: [Brief instructions for use](https://github.com/ZhongWwwHhh/Camera-Len-Wireless-Follow-Focus-System/blob/main/Documentation/Quickstart.md)

## Developer
This project always welcomes your guidance and help!!!  
This project was designed exclusively for Raspberry Pi Pico.
If you want to use it on other micropython-capable microcontrollers(such as a more powerful Arduino or pyboard), there's another [code explanation](https://github.com/ZhongWwwHhh/Camera-Len-Wireless-Follow-Focus-System/blob/main/Documentation/Codeinterpretation.md) will make this process easier

## Introduction to Project
The project currently implements a rocker potentiometer (the one on an aeromodelling remote control) to remotely and wirelessly control a stepper motor.  
It only requires two Raspberry Pi Pico, a ULN2003 and its driven stepper motor, and a pair of wireless transceiver modules, aiming to achieve the same functional equipment as an expensive commercial wireless follower.  
***In the future, it will gradually increase to be able to control the version of three motors, and add more powerful functions such as A-B point limit, see [Development Log](https://github.com/ZhongWwwHhh/Camera-Len-Wireless-Follow-Focus-System/blob/main/Documentation/Updatelog.md)***  
Receiver and transmitter use the same modular hardware design (PCB), Transmitter-receiver conversion can be achieved by simply brushing different programs  
All software will use micropython for easy modification and application, and all hardware will be designed with Kicad

## Development and business use
Please note: **All software and hardware in this repository follow GPL3. 0 (GNU General Public License v3.0)**  
You can **get usage modifications**, but everything will continue to follow GPL3. 0 Protocol  
If you make it a commodity, then you **have to** let **anyone** know **its nature and get the source code / source design file**  
See for more information [original GPL3.0 file](https://github.com/ZhongWwwHhh/Camera-Len-Wireless-Follow-Focus-System/blob/main/LICENSE)
