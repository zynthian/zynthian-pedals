# Laser-cut Zynthian-branded Switch Box
This Zynthian-branded switch box adds four user-programmable switches to your Zynthian. The box contains one 1/4" phono connector for a [sustain pedal](https://github.com/zynthian/zynthian-pedals/tree/master/sustain-pedal) and three momentary normally-off foot switches. The box is connected to the Zynth using a standard 5 pin DIN MIDI cable. This cable simply provides a way to physically connect the switches to the Zynth and is not used to transmit MIDI data. This box can be laser-cut and assembled to compliment your Zynthian.

The switch box is cut from two pieces of **3 mm material** (I used MDF) about 150 mm x 280 mm in size. My first prototype shown in the photo below used TPDT toggle-type switches. However momentary switches provide greater functionallity.

![Image of Zynthian switchbox](https://github.com/zynthian/zynthian-pedals/blob/master/SwitchBox/SwitchBox.jpg)

## Laser cut files

Laser-cut files are provided in .dxf and .svg formats. The files are colour-coded and should be cut in the following order:

1. Blue - engrave
2. Red - inside cut
3. Green - 1st outside cut
4. Black - 2nd outside cut

Cut all four colours for the first three box sides. Modify the lettering to suit. For the second three sides, just cut colours green and black.

The switchbox in the photos was made using [LaserWeb4](https://github.com/LaserWeb/LaserWeb4) and a K-40 laser cutter.

## Parts List

1. laser cut case pieces cut from the file above,
2. female 1/4" TRS phono jack (x 1) (I used [this one](https://www.aliexpress.com/item/32996271607.html?spm=a2g0s.9042311.0.0.74944c4dJB1w8D)),
3. 5 pin DIN connector - female (x1) (I used [this one](https://www.aliexpress.com/item/32907040424.html?spm=a2g0s.9042311.0.0.27424c4d9V0qom)),
4. Momentary footswitch (x3) (I used [these](https://www.aliexpress.com/item/32885860936.html?spm=a2g0s.9042311.0.0.64fc4c4dhkzR6n)), and
5. glue, wire and solder to assemble the pieces.

## Assembly

Glue the case pieces together to make the bottom case shell. Temporarilly install the DIN connector and phono jack into the bottom shell and the footswitches into the top panel. Measure and cut wires to be soldered into place as shown in the colour coded schematic and photo of the internals below. Then remove the components, solder together and reinstall. 

![Image of Zynthian switch box internals](https://github.com/zynthian/zynthian-pedals/blob/master/SwitchBox/Schematic.svg)

![Image of Zynthian switch box internals](https://github.com/zynthian/zynthian-pedals/blob/master/SwitchBox/SwitchBoxInternals.jpg)

There are no fasteners holding the box together. Small wooden blocks could be added in each corner to allow the top to be secured with screws. Internal supports to prevent deflection of the lid could aslo be added.

## Use
Set up your switches in the Zynthian webgui. For the pedal, set the MIDI CC message to 64 for sustain, 66 for sostenuto, or 67 for soft. Program the remaining three switches as desired. Use a MIDI cable to connect the Switch Box to your Zynth (extra 5 pin DIN connected to SW-1 on All-in-One board required), plug in a [pedal](https://github.com/zynthian/zynthian-pedals/tree/master/sustain-pedal) and play away! See [more info here](https://discourse.zynthian.org/t/an-extra-connector-for-some-extra-switches-or-pedal-board/3230) in the Zynthian forums.

## Share and Share Alike
Please post photos and sound samples of your make in the Zynthian forums [here](https://discourse.zynthian.org/t/funny-pedalboxes-for-zynthian-using-extra-switches/3331/7).
