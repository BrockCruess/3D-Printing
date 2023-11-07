### Goal:

Replace the loud blower fan and its duct on the side of the extruder with a quieter 40mm fan and new duct.


### Parts:

1. 3 pin Noctua NF-A4x10 FLX

2. Noctua NA-VC1 24V to 12V Buck Converter

3. Plug pin header kit and crimp tool

4. Heat shrink tubing or electrical tape

5. M3 hex screw kit

6. M2 hex screw kit (optional)


### Print:

- This part is from [here](https://www.printables.com/model/447333-ankermake-m5-noctua-heat-sink-fan-adapter/files) but the instructions are a bit misleading.
You cannot use a 4020 fan (20mm thick). There is only room under the modified extruder cover (see [here](https://github.com/BrockCruess/3D-Printing/tree/main/AnkerMake%20M5%20Mods/Quieter%20Model%20Cooling%20Fan)) for a 10mm thick fan on this new duct,
and you'll have to snip off the front right 2 posts that the lid snaps to, as well as a bit of material on the inside of the modified cover to make room for the 4010 fan. Even if you removed the extruder cover, a 20mm thick fan would reduce the effective working space of the extruder by colliding with the M5's screen housing.
- Print at 0.1mm layer height with supports.
- Snap off the 40mm fan standoffs, they're useless.
- I recommend glazing the thin corner areas with a coat of superglue to strengthen them, as well as most of the area around where the 40mm fan attaches. Light filing may be needed to get the holes right.


### Use:

- Remove the original fan and duct.
- Attach the new duct. You don't have to use all of the screw holes, but if you can get 2 M3 x 8 screws and both bottom M2 x 4 screws it'll sit nice and tight against the heatsink. You might be able to reuse the original M2 screws but you may need to widen the area for the rounded screw heads.
- Use the original M3 fan screws to fasten the Noctua fan to the new duct.
- Plug the Noctua fan straight into the buck converter's 12V output end.
- Clip the side off the plastic plug housing on the extension wire that the fan comes with so that it plugs into the buck converter's 24V input end (which is 4 pin but just line up the 3 pins correctly).
- Just look at it and you'll know which side to clip off.
- Snip the extension wire a few inches down and strip the wire ends.
- Crimp on 3 female pin headers and put some heat shrink tubing (or electrical tape) around them to make sure they don't ever make contact with each other.
- Individually plug the 3 female pins (wire colours corresponding with the original fan's wires) onto the male header pins on the extruder.
- If they don't fit very tight, lightly squeez the ends of the pin headers with pliers to tighten the holes up. They should never slip off on their own.
- Bundle the extra wire together with a cable tie or some electrical tape, tuck it under the fan, there should be just enough width for the buck converter and plenty of space for extra wire.
- Test fit the modified extruder cover and trim away anything that gets in the way of the fan.

![](https://i.ibb.co/D9cQXKK/IMG-1284.jpg)
