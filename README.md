# stepper_node
closing the loop on a bipolar nema stepper with a driver (A4988) as well as a magnetic encoder (AS5600) and an embedded MCU (undecided, probably some attiny)
my ears hurt (too much caffiene)

some goals:

    1) configurable PID through CAN bus from master controller  

    2) filter encoder data for reduce noise  

    3) state machine to keep track of # of rotations done (would help not rip wiring out)  

![](docs/system.drawio.svg)
