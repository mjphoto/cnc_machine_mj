# cnc_machine

## Software environment
### OS

Real time kernal support only comes with debian wheezy. I get better lancy times with the realtime kernel, but stretch with a preempt kernel complied is acceptable

In order to use wheezy souces.list needs to have entries changed to archive.debian.org and there are no security updates

### LinuxCNC

Stable linux cnc is 2.7. It seems that to sort out antiracking on the long axis (2 motors) we need to install linuxcnc 2.8

How to for config (as stepconf in 2.8 is a bit shit apparently):
https://forum.linuxcnc.org/49-basic-configuration/33079-how-to-2-or-more-motors-on-one-axis-gantry-linuxcnc-2-8-master

#### ToDo
* Check timings on TB6600 for ini file
* Check number of division of steps in driver that work well
* Suss out if linux cnc copes with sloping work bench
* Install stretch on big machine alongside wheezy
  * Upgrade to linuxCNC 2.8 and sort out racking correction on long axis
  * Refine ini and hal files

## Hardware stuff
### Links
* Working wiring diagram for motors
   * http://totcnc.com/img/cms/blog_img/090616/(JK02)BB5002_HY-DIV268N-5A(TB6600)part1.png

### Todo
* Work out attachemnt detail for parts we are working on
* A million other things
