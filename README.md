# AVR_steering_wheel
Implementation of a steering wheel using AVR micro controllers

## Hardware

Preferebly an ATMEGA 328p but I have jucier mcus if needed.

## Prestudy - HID

HID is a standard USB communication protocol for all major operating systems. In order for an mcu to be recognized as a gaming steering wheel,
it needs to use this protocol. So the challenge lies both in implementing the HID protcol on the mcu and in 
correctly specifying the reports within the protocol. 

## Prestudy - virtual USB

Furthermore, if an mcu that does not have built in USB support is used some kind of software USB library has to be utilized. 

