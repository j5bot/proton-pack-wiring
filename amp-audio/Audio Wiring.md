<style>
    .wire {
        display: inline-block;
        height: 10px;
        width: 10px;
        line-height: 10px;
        margin: 0 3px;
        border: solid 1px #cccccc;
    }

    .red {
        background-color: #ff0000;
    }

    .black {
        background-color: #000000;
    }

    .blue {
        background-color: #007fff;
    }

    .green {
        background-color: #66cc00;
    }
</style>

# Audio Wiring

## Features

- Mono amp
  - App control
  - Aux in
  - USB in
  - Bluetooth audio
- Higher power speaker
- Amp bypass to use original pack audio

## Diagram

![Amp Audio](Amp%20Audio.png)

([draw.io source](Amp%20Audio.drawio))

## Guide

### Parts

- amp
- speaker
- DPDT switch
- 1 x 4 pin connector

### Aux In

1. Cut 3.5mm connector cable (if necessary)
2. Connect red/black <span class="wire red"> </span><span class="wire black"> </span> wires from 3.
   5mm connector wire to 2 pin F 
   connector 
   using 
   butt 
   connectors 
   (label AUX)

### Pack Audio

1. Cut red/black wires from pack main board to pack speaker
2. Connect red/black wires <span class="wire red"> </span><span class="wire black"> </span> from pack main board to 2 pin F 
   connector using butt connectors 
   (label connector PACK)

### Speaker In

1. Connect red/black wires <span class="wire red"> </span><span class="wire black"> </span> from 2 pin F connector to new speaker

### Bypass Switch Connector

1. Connect blue wire <span class="wire blue"> </span> of 4 pin F connector to red wire <span 
   class="wire red"> </span> of 2 pin M 
   connector (label AUX)
2. Connect red wire of 4 pin F connector to red wire <span class="wire red"> </span> of 2 pin M 
   connector (label PACK)
3. Connect green wire <span class="wire green"> </span> of 4 pin F connector to red wire 
   <span class="wire red"> </span> of 2 pin 
   M connector (label SPKR)
4. Connect black wire of 4 pin F connector to red wire <span class="wire red"> </span> of 2 pin 
   M connector (label AMP)

### Bypass Switch Sub-Assembly

1. Mount bypass switch at desired location
2. Solder red wire <span class="wire red"> </span> of 4 pin M connector to right center of 
   bypass switch
3. Solder green wire <span class="wire green"> </span> of 4 pin M connector to left center of bypass switch
4. Solder a red wire <span class="wire red"> </span> jumper of left top of bypass switch to 
   right top of bypass switch
5. Solder blue wire <span class="wire black"> </span> of 4 pin M connector to right bottom of bypass switch
6. Solder black wire <span class="wire black"> </span> of 4 pin M connector to left bottom of bypass switch

### Main Wire Harness

1. Connect a blue wire <span class="wire black"> </span> 'jumper' to the black wire <span class="wire black"> </span> of a 2 pin F connector using a butt connector 
   (label AMP)
2. Connect the black wire <span class="wire black"> </span> of the 4 pin F connector 
   to the red wire <span class="wire red"> </span> of the AMP 2 pin F connector using a butt connector
3. Connect the blue wire <span class="wire blue"> </span> of the 4 pin F connector to the red wire 
   <span class="wire red"> 
   </span> of a 2 pin F connector (label AUX)
4. Connect the green wire <span class="wire green"> </span> of the 4 pin F connector to the red wire <span class="wire red"> 
   </span> of a 2 pin F connector (label 
   SPKR)