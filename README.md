# DELA EPROMMER II

![](https://github.com/DL2DW/DELA-EPROMMER-II/blob/main/Images/DELA%20EPROMMER%20II.jpg)



Replica of the then quite popular EPROM burner "DELA EPROMMER II". From an old broken circuit board I designed this reconstruction. 

It can be burned in the original state with this programming adapter the EPROM types 2716 to 27256, as well as the CMOD variants of it.

With an appropriate modification you can then even program 27512 EPROMs.

The DELA EPROMMER II was at that time also my preferred way to program EPROMs. Unfortunately the original was destroyed by a too long storage in the cellar. But for reasons of nostalgia I have rebuilt the programming adapter once again.



# Building

The board is completely equipped with components for through-hole mounting, as it was back then. There are also no special requirements. The parts are all commercially available and still easy to get in any better sorted electronics store.

Even for beginners this board should not make any problems with mounting and soldering.

The circuit board viewed from above:

![](https://github.com/DL2DW/DELA-EPROMMER-II/blob/main/Images/DELA%20EPROMMER%20II%202.jpg)



# BOM

Here is the list of components needed. I have chosen the manufacturers as examples. Of course, compatible components from other manufacturers can also be selected.

| Quantity | Designator                            | Manufacturer                  | Manufacturer  Part Number | Description                                                  |
| -------- | ------------------------------------- | ----------------------------- | ------------------------- | ------------------------------------------------------------ |
| 1        | D4                                    | NTE  Electronics              | 1N752A                    | Zener  Diode 5.6V 1/2 Watt 5% Do-35 Case                     |
| 4        | D7,  D8, D9, D10                      | ON  Semiconductor / Fairchild | 1N4002                    | DIODE  GEN PURP 100V 1A DO41                                 |
| 3        | D1,  D5, D6                           | NXP  Semiconductors           | 1N4148                    | NEXPERIA  - 1N4148 - DIODE, 1N4148 AMMO-BOX 10K              |
| 1        | D3                                    | ON  Semiconductor / Fairchild | 1N5236B                   | FAIRCHILD  SEMICONDUCTOR     1N5236B       Zener Single Diode, 7.5 V, 500  mW, DO-35, 5 %, 2 Pins, 200 C |
| 1        | D2                                    | ON  Semiconductor / Fairchild | 1N5237B                   | ZENER  DIODE, 500mW, 8.2V, DO-35; Zener Voltage Vz Typ:8.2V; Power Dissipation  Pd:500mW; Diode Case Style:DO-35; Zener Tolerance :5%; No. of Pins:2Pins;  Operating Temperature Max:200 C; Packaging:Each; Breakdown Voltage:8.2V ;RoHS  Compliant: Yes |
| 1        | U1                                    | 3M                            | 228-4817-00-0602J         | CONN  IC DIP SOCKET ZIF 28POS GLD                            |
| 1        | LED1                                  | Wurth  Electronics            | 151033RS03000             | WURTH  ELEKTRONIK  151033RS03000  LED, 3MM,   RED, 2600MCD, 621NM |
| 6        | Q1,  Q2, Q3, Q4, Q6, Q7               | Multicomp                     | BC237B                    | MULTICOMP     BC237B      Bipolar (BJT) Single Transistor,  NPN, 45 V, 200 MHz, 350 mW, 100 mA, 290 |
| 1        | Q5                                    | ON  Semiconductor / Fairchild | BC558BTA                  | FAIRCHILD  SEMICONDUCTOR     BC558BTA       Bipolar (BJT) Single Transistor,  PNP, -30 V, 150 MHz, 500 mW, -100 mA, 200 hFE |
| 2        | U2,  U3                               | Texas  Instruments            | CD4040BE                  | Counter/Divider  Single 12-Bit Binary UP 16-Pin PDIP Tube    |
| 2        | R9,  R11                              | Yageo                         | CFR-25JB-52-1K            | RES  1K OHM 1/4W 5% AXIAL                                    |
| 9        | R2,  R3, R4, R5, R6, R7, R8, R10, R12 | Yageo                         | CFR-25JB-52-10K           | RES  10K OHM 1/4W 5% AXIAL                                   |
| 1        | R1                                    | Yageo                         | CFR-25JB-52-680K          | Res  680K Ohm 1/4W 5% Axial                                  |
| 1        | CP3                                   | Panasonic                     | ECA1EHG101                | Capacitor  100 uF 25 VDC, ECA1EHG101, Panasonic Automotive & Industrial Systems |
| 2        | CP2,  CP4                             | Panasonic                     | ECA-1HHG471               | Capacitor  470 uF 50 VDC, ECA1HHG471, Panasonic Automotive & Industrial Systems |
| 1        | CP5                                   | Panasonic                     | ECA-1VHG471               | ALUMINUM  ELECTROLYTIC CAPACITOR, 470UF, 35V, 20%, RADIAL; Product Range:NHG Series;  Capacitance:470 F; Capacitance Tolerance: 20%; Voltage Rating:35V;  Diameter:10mm; Capacitor Terminals:Radial Leaded; Packaging:Each; ESR:- ;RoHS  Compliant: Yes |
| 1        | U6                                    | STMicroelectronics            | L7806CV                   | STMICROELECTRONICS  - L7806CV - LINEAR VOLTAGE REGULATOR 6V TO-220-3 |
| 1        | CP1                                   | RND  Components               | RND  150EHR100M16B        | RND  150EHR100M16B - Kondensator, 10µF, 16V, 20%, RND Components |
| 1        | U4                                    | Texas  Instruments            | SN74LS06N                 | IC  INVERTER OPEN COL 6CH 14DIP                              |
| 1        | U5                                    | Texas  Instruments            | SN74LS373N                | Latch  Transparent 3-ST 8-CH D-Type 20-Pin PDIP Tube         |



# PCB

The PCB can either be ordered directly from [PCBWay](https://www.pcbway.com/project/shareproject/DELA_EPROMMER_II.html), or you can create it yourself from the Gerber files available here.

[![PCBWay](https://www.pcbway.com/project/img/images/frompcbway.png)](https://www.pcbway.com/project/shareproject/DELA_EPROMMER_II.html)



If you liked my project, I would be very happy about a small coffee donation.

[![ko-fi](https://www.ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/R6R62T6RN)



# License

The contents of this repository, with the exception of the Docs and Software directories, are released under the following license:

- the "Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License" (CC BY-NC-SA 4.0) full text of this license is included in the [LICENSE.CC-NC-BY-SA-4.0](https://github.com/DL2DW/EasyGate1541/blob/main/LICENSE.CC-NC-BY-SA) file and a copy can also be found at https://creativecommons.org/licenses/by-nc-sa/4.0/
