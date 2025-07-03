# stepper_node
closing the loop on a bipolar nema stepper with a driver (A4988) as well as a magnetic encoder (AS5600) and an embedded MCU (undecided, probably some attiny)
my ears hurt (too much caffiene)

some goals:

configurable PID through CAN bus from master controller

filter encoder data for reduce noise

state machine to keep track of # of rotations done (would help not rip wiring out)
