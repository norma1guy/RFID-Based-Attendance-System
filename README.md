# RFID-Based-Attendance-System

## Introduction
Attendance in colleges is generally paper based which may sometimes cause errors. Taking attendance manually consumes more time. So, the proposed attendance system uses RFID technology to take attendance.
In this system, each student is issued an RFID tag. Controlling unit is in the institute. Whenever the card is placed near the reader, it will take the attendance.

## Circuit

## Circuit Components 
AT89C51 Microcontroller
AT89C51 Programming Board
11.0592 MHz Quartz Crystal
2 x 33pF Ceramic Capacitors
2 x 10KΩ Resistor
10µF Electrolytic Capacitor
2 x Push Button
16 x 2 LCD Display
3 x 1KΩ Resistor
10KΩ POT
EM-18 RFID Reader Module
RFID Tags or Cards
Connecting Wires

## Working 
When this circuit is powered ON, initially the microcontroller will display the message as Swipe the card on the LCD display. When the RFID reader detects the ID card, it will send the unique card no to the microcontroller via serial terminal.
With the help of suitable programming, we need to compare the received card no. with the numbers that are already stored in the microcontroller or any database.
Once, if any of these numbers are match with the received card no., then the corresponding name stored in that no. is displayed on the LCD display and also the attendance for the name stored in the corresponding number is marked.
By pressing the button, the attendance recording will be closed and the details are displayed on the LCD repeatedly until the microcontroller has been reset. 

## Applications
RFID based attendance system can be used in educational institutions, industries, anywhere.
RFID is emerging technology and is used in applications where authentication is needed.

## Limitations
RFID attendance system is secured, but there is a chance of misusing the cards. One person can give another person’s attendance if he/she had RFID card.
If the card was swiped for more than once, there is a chance of giving attendance for next days also if code is not written properly





