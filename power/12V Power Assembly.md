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

## Photos

[![battery wiring sub-assembly-labeled.jpg](photos%2Fbattery%20wiring%20sub-assembly-labeled-sm.jpg)](photos%2Fbattery%20wiring%20sub-assembly-labeled.jpg)

Battery-side wiring Y sub-assembly

[![load wiring sub-assembly-labeled.jpg](photos%2Fload%20wiring%20sub-assembly-labeled-sm.jpg)](photos%2Fload%20wiring%20sub-assembly-labeled.jpg)

Load-side wiring Y sub-assembly

[![switch sub-assembly-labeled.jpg](photos%2Fswitch%20sub-assembly-labeled-sm.jpg)](photos%2Fswitch%20sub-assembly-labeled.jpg)

Switch wiring sub-assembly

[![led sub-assembly-labeled.jpg](photos%2Fled%20sub-assembly-labeled-sm.jpg)](photos%2Fled%20sub-assembly-labeled.jpg)

Two-color LED indicator sub-assembly

[![charge port sub-assembly-labeled.jpg](photos%2Fcharge%20port%20sub-assembly-labeled-sm.jpg)](photos%2Fcharge%20port%20sub-assembly-labeled.jpg)

Charge & External power sub-assemblies

## Diagram

![12V Power Assembly Wiring Diagram](12V%20Power%20Assembly.png)

([draw.io source](12V%20Power%20Assembly%20-%20With&20Indicator.drawio))

## Guide

### Tools

1. Soldering iron and supplies to wire disconnect switch to quick connect wires

### Parts

1. [2 x 12V DC rechargeable battery pack (6000mAh)](https://amzn.to/4dzqkdP)
2. [2 x 12V DC M plug to 2 pigtail (18g)](https://amzn.to/4fVek8b)
3. [1 x 12V DC M to M cable, 3ft (18g)](https://amzn.to/4dRkZit)
4. [7 x F connector (pre-wired red/black, 18g)](https://amzn.to/4e0jmyx)
5. [7 x M connector (pre-wired red/black, 18g)](https://amzn.to/4e0jmyx)
6. [2 x DC barrel jack (pre-wired red/black, 18g)](https://amzn.to/4dRy4ri)
7. [1 x DPDT mini toggle switch](https://amzn.to/471Q0gT) 
   or [pre-wired SPST toggle switch](https://amzn.to/3Zr1RU2) for no-solder option
8. [butt connectors (18g)](https://amzn.to/4cEEYiH), [wire nuts](https://amz.run/9Xn1) or opt 
   for soldered wire connections
9. cable and wire management supplies ([zip ties](https://amz.run/9Xnz), 
   [zip tie mounts](https://amz.run/9XnW)) as desired
10. [1 x 12V Y-Cable -- 1F to 2M ends](https://amzn.to/3MgKJsl) (if needed for split load such
    as 12V keep-alive and amp -- also included with Talentcell battery pack, so optional)
11. [0-# x 12V extension cables](https://amzn.to/3MjNKYL) (0 or more, depending on mounting 
   locations)

## Power Sub-Assemblies

### Battery Connection Sub-Assembly

![battery sub-assembly.png](battery%20sub-assembly.png)

[![battery wiring sub-assembly-labeled-sm.jpg](photos%2Fbattery%20wiring%20sub-assembly-labeled-sm.jpg)](photos%2Fbattery%20wiring%20sub-assembly-labeled.jpg)

1. Label one 12V pigtail (part #2) BATT
2. Connect one bare-wire side of a 12V pigtail to a pre-wired FEMALE quick connector 
   (part #4)
   using your preferred wire connection strategy.  Label the two-wire quick connector CHRG.
3. Snip the black wire off of one FEMALE quick connector.  Label the connector LED B.
4. Connect the other bare-wire side of the 12V pigtail to both a new pre-wired FEMALE quick 
   connector AND the single-wire connector created in the previous step.  Connect the three red wires to 
   each other and the two black wires to each other.  Label the two-wire FEMALE quick connector BATT SW.

### Pack Load Sub-Assembly

![load sub-assembly.png](load%20sub-assembly.png)

[![load wiring sub-assembly-labeled-sm.jpg](photos%2Fload%20wiring%20sub-assembly-labeled-sm.jpg)](photos%2Fload%20wiring%20sub-assembly-labeled.jpg)

1. Label one 12V pigtail (part #2) LOAD
2. Connect one bare-wire side of the 12V pigtail to a pre-wired FEMALE quick connector
   (part #4)
   using your preferred wire connection strategy.  Label the two-wire quick connector EXT.
3. Snip the black wire off of one FEMALE quick connector.  Label the connector LED R.
4. Connect the other bare-wire side of the 12V pigtail to both a new pre-wired FEMALE quick
   connector AND the single-wire connector created in the previous step.  Connect the three red wires to
   each other and the two black wires to each other.  Label the two-wire FEMALE quick connector 
   LOAD SW.

### Bypass Switch Sub-Assembly

![switch sub-assembly.png](switch%20sub-assembly.png)

[![switch sub-assembly-labeled-sm.jpg](photos%2Fswitch%20sub-assembly-labeled-sm.jpg)](photos%2Fswitch%20sub-assembly-labeled.jpg)

1. Label a MALE quick connector BATT
2. Label a MALE quick connector LOAD
3. Snip the red wire off of one FEMALE quick connector and label it LED
4. Solder the red wire from the BATT connector onto the left center terminal of the DPDT switch
5. Solder the red wire from the LOAD connector onto the left bottom terminal of the DPDT switch
6. Connect the three black wires from BATT, LOAD, and LED quick connectors using your preferred 
   wire connection strategy

### LED Indicator Sub-Assembly

![led sub-assembly.png](led%20sub-assembly.png)

[![led sub-assembly-labeled-sm.jpg](photos%2Fled%20sub-assembly-labeled-sm.jpg)](photos%2Fled%20sub-assembly-labeled.jpg)

1. Snip the black wires off of two MALE quick connectors, labeling the red wire of one LED B and 
   the red wire of the other LED R
2. Snip the red wire off of one MALE quick connector.  Label the black wire LED C
3. Connect the red wire of the LED to the LED R quick connector red wire
4. Connect the blue wire of the LED to the LED B quick connector red wire
5. Connect the black wire of the LED to the LED C quick connector black wire


### Power Input Sub-Assemblies

[![charge port sub-assembly-labeled-sm.jpg](photos%2Fcharge%20port%20sub-assembly-labeled-sm.jpg)
](photos%2Fcharge%20port%20sub-assembly-labeled.jpg)

1. Connect the black and red wires from one pre-wired 12V port to the black and red wires on one 
   MALE quick connector.  Label it CHRG.
2. Connect the black and red wires from one pre-wired 12V port to the black and red wires on one
   MALE quick connector.  Label it EXT.

### Mounting Assemblies

1. After drilling your mounting holes, you should be able to feed the MALE connectors on the LED 
sub-assembly and the power input sub-assemblies through their respective mounting holes
2. Pass the shaft of your bypass switch through the hole and use the 
washers, nut, etc. to affix the switch and attached sub-assembly

## Connecting Sub-Assemblies

Using your quick connects and matching labels:

1. Connect the CHRG MALE quick connector on the power in sub-assembly to the CHRG FEMALE quick 
   connector on the BATT sub-assembly
2. Connect the EXT MALE quick connector on the power in sub-assembly to the EXT FEMALE quick 
   connector on the LOAD sub-assembly


1. Connect the BATT MALE quick connector on the SWITCH sub-assembly to the BATT SW FEMALE 
   connector on the BATT sub-assembly
2. Connect the LOAD MALE quick connector on the SWITCH sub-assembly to the LOAD SW FEMALE 
   connector on the LOAD sub-assembly


1. Connect the LED B FEMALE quick connector on the BATT sub-assembly to the LED B MALE connector 
   on the LED sub-assembly
2. Connect the LED R FEMALE quick connector on the LOAD sub-assembly to the LED R MALE connector 
   on the LED sub-assembly
3. Connect the LED C FEMALE quick connector on the SWITCH sub-assembly to the LED C MALE 
   connector on the LED assembly
