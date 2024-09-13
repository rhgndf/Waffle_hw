# Waffle: a pocket pager, LoRA transceiver and RF experimentation platform
Hardware designs for Waffle, a compact Pager and general RF multitool.

## Introduction
This is a reboot of a [project started in 2016](https://hackaday.io/project/11056-waffle-a-pocket-sized-digital-radio-system), aimed at creating a pocket-sized digital radio system. Due to a lack of clear objectives and motivation, this project never got any further. However, there is today a certain revival of POCSAG in the amateur radio community, with the [DAPNET project](http://hampager.de). No open-source pager design exist to this day. This project aims to bridge that gap, and bring an open design that could be adapted to anyone's needs. 

## Feature list

 - UHF (430-440) support
 - User interface with three buttons and an easy-to-read display
 - Programmable either via the display, or via Wifi and web portal. 

## Hardware
Uses an ESP32-S3, coupled with an SX1276 for reception and transmission of signals. Battery is a classic 3.7V Li-Ion cell with integrated battery management and charging. USB-C port for programming and charging. OLED or LCD display (TBD).

## Revision list

 - The [initial design from 2016](https://hackaday.io/project/11056-waffle-a-pocket-sized-digital-radio-system) is known as rev XX
 - 0.1a: current version. Aims to validate the basic hardware choices and being dev on software.

