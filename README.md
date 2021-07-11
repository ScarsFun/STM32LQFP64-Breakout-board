# STM32 LQFP64 BREAKOUT BOARD

This is a 64pin STM32 BREAKOUT BOARD inspired by "blue pill" STM32 48pin board (Maple mini clone).
Same features are Improved:

* 3.3v Power supply and VDDA improvements. 
* USB ESD protection.
* added USB reset circuit (not needed for some MCUs).
* Many Cortex M0, M3, M4 STM32 Microcontrolles may be mounted in this PCB layout.
Check notes in schematic and read STM32 datasheets. 
* Eagle PCB, Schematics.

* RTC oscillator is not implemented because no enought PCB spaces to follow STM design guide. ...I'll be pleased if anyone will find a solution 

# CHANGELOG
## 1.3.1 (2021-07-11)
### Fix:
- Fixed reset circuit.
- Silkscreen improvements.

## 1.3 (2020-06-16)
### Features:
- Added support for STM32F401, STM32F410, STM32F411, STM32F412, STM32F413, STM32F423, STM32F446
### Fix:
- Added partitor to VBUS  

## 1.2 (2018-10-11)
### Fix:
- RTC oscillator design dont works. removed from project 

## 1.1 (2018-07-23)
### Features:
- First release lot of bugs


This work is licensed under a [Creative Commons Attribution 4.0 International License.](http://creativecommons.org/licenses/by/4.0/)

![CC](/images/cc.png)

 ![PCB_front](/images/Scarsfun11a.png)
 ![PCB_sch](/images/schematics.png)

