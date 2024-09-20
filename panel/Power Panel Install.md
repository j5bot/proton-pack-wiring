# Power Panel Install

![panel lit.jpg](photos/panel%20lit.jpg)

[
![panel - pack open-sm.jpg](photos/panel%20-%20pack%20open-sm.jpg)
](photos/panel%20-%20pack%20open.jpg)

This panel uses the [12V Power Assembly](../power/12V%20Power%20Assembly.md) circuit I detail 
elsewhere on this 'site' to provide functionality to charge your pack with electronics isolated, 
run your pack from your internal battery, and to run your pack from an external battery with the 
internal battery isolated.

[Appendix: Possible Additions...](#possible-additions)

You can use it with 5V/6V pack electronics with the addition of a 12V to 6V step down converter.

## Videos

- [Power Panel Demo (Quick)](https://youtube.com/shorts/JSzOQSbEpJE)
- [Power Panel Demo (Long)](https://youtu.be/zHAtCDo_cRU)

## WARNING

**BEFORE PROCEEDING, [READ THIS](Battery%20Warning.md)**

**YOU DID [READ THIS](Battery%20Warning.md), RIGHT?**

## Pack Mods / Cuts

There are several areas you’ll need to cut into the proton pack if installing into the power cell “snack” compartment or a HasLab.

[
![corner notch.jpg](photos/corner%20notch-sm.jpg)
](photos/corner%20notch.jpg)

(Photo 1)

[
![talentcell circuit board location.jpg](photos/talentcell%20circuit%20board%20location-sm.jpg)
](photos/talentcell%20circuit%20board%20location.jpg)

(Photo 2)

[
![wiring positions-sm.jpg](photos/wiring%20positions-sm.jpg)
](photos/wiring%20positions.jpg)

(Photo 3)

[
![battery compartment notch.jpg](photos/battery%20compartment%20notch-sm.jpg)
](photos/battery%20compartment%20notch.jpg)

(Photo 4)

| Area                                                                                                                                                                                                                                                                                                                                      | Image                                                                              |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|
| First, there is a corner between the booster tube cavity and snack compartment cavity.  Making this cut allows for mounting switches and ports lower on the panel (Photo 1: CORNER NOTCH).                                                                                                                                                | ![corner notch-sub.jpg](photos/corner%20notch-sub.jpg)                             |
| You can reference the photo to see how far you need to cut to mount the ports in the locations where I did (Photo 1: PORT & SWITCH INSTALL LOCATIONS).                                                                                                                                                                                    | ![port and switch install-sub.jpg](photos/port%20and%20switch%20install-sub.jpg)   |
| Secondly, you’ll make the “notch” that the power cell cable normally goes through into the main top cavity deeper, allowing you to pass the power assembly wires through from the snack area into the main body (Photo 2: MODIFIED WIRE PASS-THROUGH NOTCH).                                                                              | ![wire pass-through notch-sub.jpg](photos/wire%20pass-through%20notch-sub.jpg)     |
| Optionally, in order to provide a clearer space in the snack cavity, you can remove the main board and then carefully cut a small hole between it and the ion arm / right cavity.  Once cut, turn the power cell electronics JST connector sideways, pass it through the hole carefully and plug it back in (Photo 3: POWER CELL WIRING). | ![power cell wiring-sub.jpg](photos/power%20cell%20wiring-sub.jpg)                 |
| Thirdly, you’ll cut a notch out of the bottom of the D Cell battery compartment bottom to clear more room for switches and ports on the panel (Photo 4: BATTERY COMPARTMENT NOTCH).                                                                                                                                                       | ![battery compartment notch-sub.jpg](photos/battery%20compartment%20notch-sub.jpg) |


## Replacement Panel

I chose to use an [
MDF replacement panel from ImperialTechShopUS
](https://www.etsy.com/listing/1415573195/talent-cell-hole-snack-compartment).  It was easy to work with and good 
quality overall but there were minor problems with either it or the pack itself not being square.
Probably the pack.

### Design

I designed a sticker to be placed on the panel, through which holes would be drilled for 
mounting the various components.  I didn't design any graphics or specific placement for the LED 
indicator.

The sticker is taller than it needs to be, on the bottom, because it includes space representing 
the bottom of the 'bump-out' on an original panel.

![panel design - cropped](graphics/panel%20design%20-%20cropped.png)

[full sticker](graphics/panel%20design.png)

## Standby Switch

The 'STANDBY' switch is a secondary power switch for your internal battery.  In order to have 
one, you'll need to solder onto the contacts which come out of the back of the battery's circuit 
board where the primary switch is located.

**YOU DID [READ THIS](Battery%20Warning.md), RIGHT?**

I don't have any instructions on this at the moment.  When you solder onto it, you'll add a 
quick connect.  The other side of the quick connect will plug into the actual switch.

## Mounting Holes

Center punch or otherwise mark the holes you'll be drilling by pressing through the 'crosshairs' 
in the design.  Then, carefully cut out the guide circles with something like a craft knife / 
x-acto.

This will help get a nice clean hole through the sticker and a properly aligned drill.

Be careful with where you drill your LED indicator hole, since I didn't mark it and the 
placement is a bit tricky.

## Quick Connect Modifications

The MALE quick connects on the ports and LED are going to have to go through the holes you drill 
in the panel.

For the ports, in order to do so, the portion of the quick connect which sticks out from the main 
body at angles will have to be snipped off.

For the LED indicator, the tabs at the end of the quick connects (not the one on the top!) will 
also need to be snipped off.  The image below shows one side, but there are tabs on the hidden 
side, too.

![quick connects.jpg](photos/quick%20connects.jpg)

## Assembly

1. Run the wiring through the holes in the panel for your ports and LED indicator.  Snip off 
   bits of the quick connects as needed to get everything through.

   You may need to omit the LED indicator 'nut' if your indicator sits close to the pack 
   internals1 or you can't get it over the quick connects and wires at the same time.  You can always use something like electrical tape or a rubber band to hold it in a little bit more.  Experiment.
2. Run the two switches through the holes from the back side of the panel.  Don't connect the 
   main power switch yet.
3. Test fit your panel and make sure that everything seems ok.

### Bench Testing the Circuit (No Pack Electronics)

This portion may have done previously, but it's a good idea to do it again, regardless.

1. Remove the panel and assemble the wiring by connecting the quick connects, but don't connect to 
   batteries or pack electronics yet.
2. Make sure that the 'PRIME' switch is flipped down and plug an external battery source 
   (this can be your internal battery if needed) into the yellow 'EMRGNCY' port.  Turn on the 
   battery and you should get a red indicator.  If you don't get that, you'll have to 
   troubleshoot the 'LOAD' side of your circuit.
3. Turn off and disconnect the battery from the 'EMRGNCY' port.
4. Connect the battery to the 'BATT' side 12V plug.  Turn the battery on using the built-in 
   switch.  You should see the blue indicator.  If you don't you'll have to trouble-shoot the 
   'BATT' side of the circuit.
5. Flip the 'PRIME' switch on.  You should now see the indicator turn red.
6. Flip the 'PRIME' switch off.  You should see the blue indicator light. Turn the battery off.  You 
   should see no indicator lights.

### Bench Testing the Circuit (Pack Electronics)

1. Connect the pack electronics to the 12V 'LOAD' side plug.  For HasLab packs, make sure that 
   the cyclotron cover is seated well and won't disconnect during the tests.
2. Turn the battery on.  You should see the blue indicator and should NOT be able to power up 
   the pack.
3. Flip the 'PRIME' switch.  You should see the indicator light change to red.
4. Turn the pack on and everything should power up properly.
5. Turn the pack off (NOT with the battery switch or by flipping 'PRIME'!)
6. Flip down the 'PRIME' switch.  The indicator should turn blue.
7. Turn off the battery.  The indicator light should turn off.
8. Plug a battery into the 'EMRGNCY' port.  Turn the battery on.  The indicator should turn red.
9. Turn the pack on and everything should power up properly.
10. Turn the pack off (NOT with the battery switch!)
11. Turn the battery off and disconnect it from the port.

### Pack Installation

1. Disconnect the 'BATT' 12V, 'LOAD' 12V, and anything else you may have plugged in that isn't 
   part of the circuit wiring.
2. Install the panel in the snack compartment.
3. Connect the internal battery's secondary switch which you added to the 'STANDBY' switch quick 
   connect.
4. Route the rest of your wiring where it makes the most sense to you.  Don't try to do any 
   cable management yet, as you may need to troubleshoot something.
5. Connect the internal battery to the circuit with the 'BATT' side 12V plug.
6. Check that flipping the 'STANDBY' switch lights up the blue indicator.
7. Flip the switch back off.
8. Connect the 'LOAD' 12V plug to your pack electronics.

Now run through the same sequence as 'Bench Testing the Circuit (Pack Electronics)' as above in 
order to test that everything in the circuit is functioning with the way you've installed it.

1. Test fit the motherboard without closing the pack up.  If it doesn't sit properly, troubleshoot 
why it doesn't.
2. Do any cable / wire management tasks that you want to do.
3. Repeat some basic testing if you'd like.
4. Close up your motherboard.

Test the functionality out again ... and enjoy your new power panel!

## Appendix: Possible Additions

Using this [fiber optic tubing](https://amz.run/9apS) and additional holes drilled
for mounting the ends, you can add the ability to see the battery charge level to the panel.  
Connect the tubing to the charge light holes (Photo 2: CHARGE LIGHT HOLES).

Add a port to charge USB devices by connecting one of [
these USB panel mount ports](https://amz.run/9apU) to a [
USB bare wire pigtail](https://amz.run/9apW) using quick connects.

Add voltmeters, ammeters, etc.