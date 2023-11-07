### Goal:

Replace the original power supply with one that has a thermal-controlled fan in it so it only runs when actually needed.

This guide is originally from [here](https://wiki.printed.boats/en/Modding/silence-power-supply), I'm just adding it to my mod list to keep everything together in one repo.


### Parts:

1. MeanWell LRS-350-24 Power Supply (from [Amazon](https://www.amazon.ca/LRS-350-24-350-4W-Single-Output-Switchable/dp/B013ETVO12/ref=sr_1_3?crid=6IIYLIUQERWR&keywords=MEAN+WELL+LRS-350-24&qid=1699327295&sprefix=mean+well+lrs-350-24%2Caps%2C82&sr=8-3))

2. A multimeter


### Use:

- Unplug the printer and remove the bottom plate.

- Remove the old power supply, keep track of which wires went where.

- Set the new power supply voltage to the voltage used in your country using the red switch on the side.

- Install the new power supply but only connect the ground (⏚), L and N wires.

- Plug in the printer, set the power switch on the back to the on position, and use a multimeter to check the voltage of the +V and -V terminals on the new power supply.

- Turn the potentiometer on the power supply until the voltage reads exactly 24V.

- Set the power switch to the off position and unplug the printer.

- Connect the V+ and V- terminals as they were on the original power supply.

- Cover the terminals with kapton tape or electrical tape since they don't have the nice cover that the original power supply had.

- Reattach the back plate and boot up the printer.

![](https://wiki.printed.boats/ps-tape.jpg)
