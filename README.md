# Esp32-Custom-Board

This repository contains the design files and documentation for a custom ESP32 Board. 
## Overview
This custom ESP32 board is designed to practice and develop my skill set in Schematic and PCB design. This board can be used for any application you like , It can function as ESP32 dev board .

## Features and components:
+ Transistor  -SS8050-G
+ Header
+ Esp32 Module
+ USB to Serial
+ Reset and Boot Button
+ Power and User Led
+ Buck Converter 
+ ESD protection for the signal that runs from USB to the USB to serial converter
The board can be programmed using the Arduino IDE or any other ESP32-compatible toolchain. It supports Wi-Fi, Bluetooth, and many other peripherals of the ESP32.
## Schematic and PCB Layout
The schematic and PCB layout of the board are provided. The board was designed using EasyEDA software
## How to Use
To use the board, you will need a USB cable, a 3.3V power supply, and a serial terminal program. Follow these steps:
1.	Connect the USB cable to the board and your computer. The board should be recognized as a COM port.
2.	Connect the 3.3V power supply to the 4-pin connector. Make sure the polarity is correct.
3.	Open the serial terminal program and select the COM port and the baud rate of 115200.
4.	To program the board, press and hold the boot button, then press and release the reset button. The board should enter the boot mode and display “waiting for download” on the serial terminal.
5.	Upload your code using the Arduino IDE or any other ESP32-compatible toolchain. The board should display “hard resetting via RTS pin” on the serial terminal when the upload is done.
6.	To run the code, press and release the reset button. The board should execute your code and display the output on the serial terminal.
## Examples and Resources
To get started with the board, you can try some of the examples from the Arduino-ESP32 library. You can also find more information and resources about the ESP32 on the Espressif website.
I hope this text is helpful for your project. If you have any questions or feedback, please let me know.


