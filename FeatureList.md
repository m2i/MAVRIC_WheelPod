# Wheel Pod Feature List
## Hardware
- Full Duplex RS-485/RS-422 Converter 3.3V Supply
- _Intersil ISL83490IBZ_
- Half Duplex RS-485/RS-422 Transceiver 5V supply
- _STMicroelectronics ST485CDR_
- Hall Effect Current Transducer
- _Allegro MicroSystems ACS711ELCTR-25AB-T_
- Inductance to Digital Converter
- _Texas Instruments LDC1000_
- 3.3v Regulator
- _STMicroelectronics L78L33ACUTR_
- 5v Regulator (Required for analog voltage on LDC)
- _STMicroelectronics L78M05CDT-TR_
- Microcontroller
- _STMicroelectronics STM32F030K6T6_

## Features
- Cat5 jack for input from Chipkit (RS-485, 3.3V, GND)
- Stepper Motor current sense
- Wheel Motor current sense
- Serial connection to SyRen
- Connection to stepper controller (Enable, Direction, Step, 3.3V)
- Specification suggests 5V, any voltage is fine as long as current is between 5 - 20mA
- Inductance sensor for wheel rotation position
