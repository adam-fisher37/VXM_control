# VXM_control
Est. 2022
Remote control of a VXM stepper motor using python. Motor used is a Bi-slide E04

Current control functions include:
moving stage to its stored zero position, moves stage relative to its starting position, moving stage relative to starting position in small equal sized increments with a pause in between each movement, and obtaining the motor's distance, in steps, away from the current stored zero position.

current packages needed:

pyserial, time, re, numpy