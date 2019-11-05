# Laser-cut Zynthian-branded Sustain Pedal

This Zynthian-branded sustain pedal can be laser-cut and assembled to compliment your Zynthian. This pedal was modeled after an old Yamaha sustain pedal. For versatility, I added a phono jack to the case rather than soldering a patch cable directly into it.

The pedal case is cut from a piece of **3 mm material** (I used MDF) about 130 mm x 210 mm in size. My first prototype shown in the photo below used a tact switch. However this proved to be very noisy when used as the case acted like a resonator and amplified the click of the tact switch. My second version described below implements a DIY switch using copper mains wire.

![Image of Zynthian sustain pedal](https://github.com/zynthian/zynthian-pedals/blob/master/sustain-pedal/pedal_1.jpg)

## Laser cut files

Laser-cut files are provided in .dxf and .svg formats. The files are colour-coded and should be cut in the following order:

1. Blue - engrave
2. Red - inside cut
3. Green - 1st outside cut
4. Black - 2nd outside cut

The pedals in the photos were made using [LaserWeb4](https://github.com/LaserWeb/LaserWeb4) and a K-40 laser cutter.

## Parts List

1. laser cut case pieces cut from the file above,
2. female 1/4" TRS phono jack (x 1) (I used [this one](https://www.aliexpress.com/item/32996271607.html?spm=a2g0s.9042311.0.0.74944c4dJB1w8D)),
3. short pieces of copper mains wire (x 2),
4. M4 x 10 mm machine screw (x 2) (I used old hard drive mounting screws),
5. small pieces of IC packaging foam (or a suitable spring to return the pedal to the off position, and
6. glue and double-sided tape to assemble the case pieces and attach foam pieces into case.

## Assembly

Glue the case pieces together to make the top and bottom case shells. Temporarily install the phono jack into the bottom shell. Cut and bend the two copper mains wires to shape as shown in photo below. Then remove the jack and solder mains wires to phono jack terminals. Once the wires have been soldered onto the jack, install the jack and wire switch assembly into the case. Note: for universal function, the R (ring) S (sleeve) terminals could be soldered together to allow use of both TS and TRS patch cables. 

![Image of Zynthian sustain pedal](https://github.com/zynthian/zynthian-pedals/blob/master/sustain-pedal/pedal_2.jpg)

After the jack and wire switch assembly is installed, cut a small piece of IC packaging foam and attach it under the wire coming from the S (sleeve) terminal with double-sided tape. Ideally, this wire should be roughly flush with the top edge of the bottom case shell. The wire from the T terminal should be bent up slightly so that it does not touch the S wire until the pedal is depressed. On release of the pedal, this wire should spring back into the open position on its own.

Now cut two more foam pieces about 18 mm high and tape them to  either side of the bottom case shell as shown in the photo below. These foam pieces act as a spring to return the pedal to the open (or off) position. Naturally, a spring can be ussed instead of the foam pieces, but I didn't have a suitable spring at home and the foam seems to work just fine.

![Image of Zynthian sustain pedal](https://github.com/zynthian/zynthian-pedals/blob/master/sustain-pedal/pedal_3.jpg)

Finally, place the case top onto the bottom case shell assembly and install the two hinge screws, one on either side of the case. Note that the holes in the bottom case shell are clearance holes which act as hinge points as well as holding the case shells together, whereas the holes in the top case shell are not. The screws should easilly tap into the top case shell, but don't over-tighten as these holes are easy to strip. If the case is cut from 3 mm acrylic, these holes may require to be tapped.

## Use
In the Zynthian webgui, set the MIDI CC message for your pedal to 64 for sustain, 66 for sostenuto, or 67 for soft. Plug one end of a TS or TSR patch cable into your new pedal and the other end into your Zynth stomp box (or any other device that accepts pedal input) and play away!

## Share and Share Alike
Please post photos and sound samples of your make in the Zynthian forums [here](https://discourse.zynthian.org/t/funny-pedalboxes-for-zynthian-using-extra-switches/3331/7).
