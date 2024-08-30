# Audio Wiring with Amp Bypass

## Overview

We will be disconnecting the pack audio from the
built in speaker.  Then we will connect the pack
audio to the aux input of a 30W mono amplifier
before routing it to a new higher power speaker.

Along the way, we'll pass the signals through a
bypass switch, allowing the pack audio to be
reconnected directly to the speaker while taking
the amplifier out of the audio circuit.

## Features

- Mono amp
  - App control through phone
  - Aux in
  - Play files from USB
  - Bluetooth audio from phone
- Higher power speaker
- Amp bypass to use original pack audio

## Diagram

![Amp Audio](Amp%20Audio.png)

([draw.io source](Amp%20Audio.drawio))

## Guide

### Tools

- Wire cutter
- Wire stripper
- Crimper
- Soldering iron and supplies
- Fasteners for mounting the amp
- Drill for mouting the bypass switch

### Parts

1. [Mono amp](https://amzn.to/3Mmv7n8)
2. [3" speaker](https://amzn.to/4cKyq2i)
3. 3.5mm mono (or stereo) "headphone" pre-wired [jack](https://amz.run/9VQ6)
  or [cable](https://amz.run/9VQ9)
4. [1 x DPDT switch](https://amzn.to/3yMudNG) (common for other wiring)
5. [1 x 4 pin connector](https://amzn.to/3Z5QMY5) (common for other wiring)
6. [4 x 2 pin F connector](https://amzn.to/3Mq3lpL) (common for other wiring)
7. [4 x 2 pin M connector](https://amzn.to/3Mq3lpL)
8. [butt connectors (18g)](https://amzn.to/4cEEYiH)

<!--
### Wire List

- AUX 2 pin F
  - red - aux in connector
  - black - aux in connector
- AUX 2 pin M
  - red - bypass connector
  - black - pack audio ground
- PACK 2 pin F
  - red - pack audio
  - black - pack audio
- PACK 2 pin M
  - red - bypass connector
  - black - pack audio ground
- SPKR 2 pin F
  - red - speaker in
  - black - speaker in
- SPKR 2 pin M
  - red/red - bypass connector
  - black - pack audio ground
- AMP 2 pin F
  - red
  - black
- AMP 2 pin M
  - red
  - black
- 4 pin F
- 4 pin M
-->

### Aux In

1. Cut 3.5mm connector cable (if necessary)
2. Connect red/black (and white if stereo) wires ![wire](../images/red-wire.png) ![wire](../images/black-wire.png) from
   3.5mm connector cable to 2 pin F connector using butt connectors (label AUX)
   
<!--
- AUX 2 pin F red/black
-->

### Pack Audio

1. Cut red/black wires ![wire](../images/red-wire.png) ![wire](../images/black-wire.png) from pack main board to pack speaker
2. Connect red/black wires ![wire](../images/red-wire.png) ![wire](../images/black-wire.png) 
   from pack main board to 2 pin F connector using butt connectors (label connector PACK)
   
<!--
- PACK 2 pin F red/black
-->

### Speaker In

1. Connect red/black wires ![wire](../images/red-wire.png) ![wire](../images/black-wire.png) 
   from 2 pin F connector to the new speaker (label connector SPKR)
   
<!--
- SPKR 2 pin F red/black
-->

### Bypass Switch Connector

1. Connect blue wire ![wire](../images/blue-wire.png) of 4 pin F connector to red wire ![wire](../images/red-wire.png) of
   2 pin M connector (label AUX)
2. Connect red wire ![wire](../images/red-wire.png) of 4 pin F connector to red wire ![wire](../images/red-wire.png) of
   2 pin M connector (label PACK)
3. Connect green wire ![wire](../images/green-wire.png) of 4 pin F connector to red wire 
   ![wire](../images/red-wire.png) of 2 pin M connector (label SPKR)
4. Connect black wire ![wire](../images/black-wire.png) of 4 pin F connector to red wire
   ![wire](../images/red-wire.png) of 2 pin M connector (label AMP)
   
<!--
- 4 pin F blue/red/green/black
- AUX 2 pin M red
- PACK 2 pin M red
- SPKR 2 pin M red
- AMP 2 pin M red
-->

### Bypass Switch Sub-Assembly

2. Solder red wire ![wire](../images/red-wire.png) of 4 pin M connector to right center of bypass switch
3. Solder green wire ![wire](../images/green-wire.png) of 4 pin M connector to left center of bypass switch
4. Solder a red wire ![wire](../images/red-wire.png) jumper of left top of bypass switch to 
   right top of bypass switch
5. Solder blue wire ![wire](../images/black-wire.png) of 4 pin M connector to right bottom of bypass switch
6. Solder black wire ![wire](../images/black-wire.png) of 4 pin M connector to left bottom of bypass switch
1. Mount bypass switch at desired location

<!--
- 4 pin M red/green/blue/black
-->

### Main Wire Harness

#### Bypass Switch Section
1. Connect a blue wire ![wire](../images/blue-wire.png) 'jumper' to the black wire ![wire](../images/black-wire.png) of a
   2 pin F connector using a butt connector (label AMP)
2. Connect the black wire ![wire](../images/black-wire.png) of the 4 pin F connector 
   to the red wire ![wire](../images/red-wire.png) of the AMP 2 pin F connector using a butt connector
3. Connect the blue wire ![wire](../images/blue-wire.png) of the 4 pin F connector to the red wire
   ![wire](../images/red-wire.png) of a 2 pin F connector (label AUX)
4. Connect the green wire ![wire](../images/green-wire.png) of the 4 pin F connector to the
   red wire ![wire](../images/red-wire.png) of a 2 pin M connector (label SPKR)

<!--
- AMP 2 pin F red/black
- SPKR 2 pin M red
-->

#### The Rest
1. Connect the black wire ![wire](../images/black-wire.png) of the AUX 2 pin M connector,
   the black wire ![wire](../images/black-wire.png) of the PACK 2 pin M connector, and
   a black wire ![wire](../images/black-wire.png) 'jumper' using a butt connector
2. Connect the black 'jumper' wire ![wire](../images/black-wire.png) from above to the
   black wire ![wire](../images/black-wire.png) of the SPKR 2 pin M connector, and the black wire
    ![wire](../images/black-wire.png) of the AMP 2 pin M connector using a butt connector
   
<!--
- AUX 2 pin M black
- PACK 2 pin M black
- SPKR 2 pin M black
- AMP 2 pin M black
-->

### Assembling the Circuit

Connect the paired 2 pin M and F connectors

- AUX F to M
- PACK F to M
- SPKR F to M
- AMP F to M

Connect the 4 pin bypass switch connectors

   