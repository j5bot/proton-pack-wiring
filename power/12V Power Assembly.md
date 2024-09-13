# 12V Power Assembly Wiring

## Features

- Charging port for primary internal battery
- Bypass switch to isolate the pack electronics
from the battery while charging
- Secondary battery port - just flip the bypass switch
and then plug in your emergency power

## Overview

For this project we will create two identical
Y connectors with 12V DC input, 12V DC output and
connect them together with a bypass switch.

## Diagram

![12V Power Assembly Wiring Diagram](12V%20Power%20Assembly.png)

([draw.io source](12V%20Power%20Assembly.drawio))

## Guide

### Parts

1. [2 x 12V DC rechargeable battery pack (6000mAh)](https://amzn.to/4dzqkdP)
2. [2 x 12V DC M plug to 2 pigtail (18g)](https://amzn.to/4fVek8b)
3. [1 x 12V DC M to M cable, 3ft (18g)](https://amzn.to/4dRkZit)
4. [7 x F connector (pre-wired red/black, 18g)](https://amzn.to/4e0jmyx)
5. [7 x M connector (pre-wired red/black, 18g)](https://amzn.to/4e0jmyx)
6. [2 x DC barrel jack (pre-wired red/black, 18g)](https://amzn.to/4dRy4ri)
7. [1 x 12V Y-Cable -- 1F to 2M ends](https://amzn.to/3MgKJsl) (also included with Talentcell battery pack, so optional)
8. [3 x 12V extension cables](https://amzn.to/3MjNKYL) (maybe more, depending on mounting locations)
9. [1 x DPDT mini toggle switch](https://amzn.to/471Q0gT)
10. [butt connectors (18g)](https://amzn.to/4cEEYiH)
11. cable and wire management supplies (zip ties and/or hook-and-loop strips; cable clips) as desired

## Power Sub-Assemblies

### Battery Connection Sub-Assemblies

![12V Power Assembly - BCC1 Diagram](12V%20Power%20Assembly%20-%20BCC1.png)
![12V Power Assembly - BCC2 Diagram](12V%20Power%20Assembly%20-%20BCC2.png)


1. Connect one 12V DC M to two pigtails (part #2) to two F (part #4) pre-wired connectors 
using butt connectors (part #10) to join (label it BCC1, connectors IN and IN)
2. Repeat step one (label it BCC2, connectors OUT and OUT)

BCC1 is the primary battery and charging sub-assembly

BCC2 is the power out and secondary battery sub-assembly

### Bypass Switch Sub-Assembly

![Bypass Switch Sub-Assembly](Bypass%20Switch%20Sub-Assembly.png)

1. Mount the DPDT switch (part #9) where desired
2. Label a M connector (part #5) OUT
3. Label a M connector (part #5) IN
4. Solder the black wire from the IN M connector onto the left top terminal of the DPDT switch
5. Solder the black wire from the OUT M connector onto the left center terminal of the DPDT switch
6. Solder the red wire from the IN M connector onto the right top terminal of the DPDT switch
7. Solder the red wire from the OUT M connector onto the right center top terminal of the DPDT 
   switch

### Power Input Sub-Assemblies

1. For both DC ports, mount the DC barrel jack / port where desired, and then connect to M 
connector (part #5), using butt connectors (label the wires PWR1 and PWR2)


## Connecting Sub-Assemblies

1. Connect one F IN connector on BCC1 to the M IN connector on the switch assembly
2. Connect one F OUT connector on BCC2 to the M OUT connector on the switch assembly
3. Connect PWR1 (CHARGE - charge jack) M connector to F IN connector on BCC1
4. Connect PWR2 (2ND - secondary battery port) M connector to F OUT connector on BCC2
