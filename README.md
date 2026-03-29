# Intamsys_FunMat_HT_Mods
Modern upgrades for the Intamsys Funmat HT

I bought a "broken down" Intamsys FunMat HT.

The original user could not get it to print reliably. After some iteration I determined it was due to bad first layers.

So far, I have replaced the original motherboard with a BTT Octopus Pro and the DM422S drivers with TMC2209 drivers, also from BTT.

Paired with a Raspberry Pi for Klipper.

I had originally configured it to use the mechanical switch in the toolhead assembly to work as a z-probe and leveraged it for mesh bed leveling, but the force required to trigger this mechanical switch was causing massive dips in the rear corners. With a bed mesh range as high as 4mm in some instances due to this. I came across Beacon H and saw that the contact probe requires 30g to actuate and figured this might cause a good replacement. Thinking that the eddy current wouldn't function well on the carbon fiber plate. However, I was pleasantly surprised.

Anyways, you're looking at a motherboard replacement, Klipper config, and Beacon H.
