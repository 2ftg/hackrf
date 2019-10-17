*HackRF lite*
This repository contains hardware designs and software for OH2FTG's version of HackRF,
a low cost, open source Software Defined Radio platform.

Main aim is to replace the Maxim MAX2837+MAX5864 combo with a Microchip/Atmel AT86RF215-series TX/RX chipset. 
And possibly replacing the Xilinx XC2C64A CPLD used as gluelogic with a larger one or an FPGA from Intel or Lattice with LVDS transceivers for the LVDS interface gluelogic. 

Using AT86RF215 might allow genuine synchronized fullduplex use. 

![HackRF One](https://raw.github.com/mossmann/hackrf/master/doc/HackRF-One-fd0-0009.jpeg)

(photo by fd0 from https://github.com/fd0/hackrf-one-pictures)

AT86RF215-series datasheet:
http://ww1.microchip.com/downloads/en/DeviceDoc/Atmel-42415-WIRELESS-AT86RF215_Datasheet.pdf

Modz by Ismo Väänänen OH2FTG @2ftg1
principal author: Michael Ossmann <mike@ossmann.com>

http://greatscottgadgets.com/hackrf/
