# stereo-splicer
Stereo granulator effect, realized with Faust (Functional Audio Stream) functional programming language.

Splits a mono input signal into two parrallel running granulators (Alpha & Beta). Each granulator has individual pitch, windowing and effect controlls, while size, spread, delay and grain density are left as global parameters for both granulators. 

A stereo mixer is also implemented in order to allow the artist to control the level of each granulator on both the left and right channels.

The device is midi enabled and actively mapped to the KORG nanoKONTROL2.

Osc controll is also implemented, with a python script which allows for take-over controlls of the mixer section, with streamed osc data from excel tables with the use of the python-osc library.
