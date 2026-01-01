![]()
#JOYSTICK PCB

The Joystick PCB is a prototype to facilitate the usage of joysticks along with classic devboards.

The PCB contains a 01*05 socket pin connector folliwing this order (up to down):
-VCC
-X axis
-Y axis
-SW_OUT
-GND

A pull-up resistor is used close to the push switch with a value of 10Kohms.

This project is a beginner project so i don't recommend using the V1.0 since others professional PCBs are existing. (see *CONTEXT*)


#CONTEXT
This project is my first project desinging a custom PCB to complete a task.

First of all i got a joystick by breaking an old controller ( joystick RSF ) , and i wanted to use it with my ESP32.
The problem is that there are too many pins on this joystick , and i did not want to do another perfboard horrible project so i decided to learn how to do a real PCB using KiCad, a free PCB design suite.

![]()

After learning the basics i did multiple versions of the schematic and ended up finding some open source symbols and footprints for the joystick itself because KiCad is not providing symbol and footprint for this joystick .

![]()


Then i completed the first version of the PCB using [this footprint for the joystick](https://github.com/redsaber42/GameController/blob/main/Joystick.kicad_mod)

![]()

#USED SOFTWARE
[](https://img.shields.io/badge/KiCad-9.0-blue)



