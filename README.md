rlabLaserCutter
===============

General Principles:
* Laser only (no scope creep to routing etc)
* Goal is to improve on deficits in current laser cutter, rather than reinvent the wheel
* Usability for the general user must be the same as or improved on what we have at the moment
* Must fit in the small machine room (work top can be removed so can be floor standing)
* Design and build process will be released afterwards as open source

Chassis/Mechanics:
* 1240mm x 620mm cutting area
* 3 tap inputs for different gas bottles/pumps
* Electronically adjustable z height
* Z-probe for focussing
* Top loading of materials
* 200mm deep bed
* Dual targeting lasers in order to show the point of convergence for aligning the lasers waist.
* 20x40 & 40x40 extrusion for the frame
* The ability to accept custom jigs for repeatable work and reuse of home position, as well as a standard jig for a standard home position.
* Better extraction to have more uniform downward flow as well as across the piece.
* Class 1, totally light sealed while in operation to prevent exposure
* Tube to be mounted horizontally
* Open loop cooling with a sump
* Fire suppression system on CO2 (scavenge parts from a soda stream?)
* Allowance in case design for 7" screen and Raspberry pi or tablet later

Electronics/Laser:
* 60W CO2 laser
* Software control of laser power
* LAoS or Smoothie control board
* Internal cameras with good internal lighting both for project time-lapse etc as well as real time monitoring/positioning
* Internal cameras on tube ends to check for air bubbles
* Interlocks on all panels to protect from exposure

Software/Control:
* PC toolchain will be Illustrator and Inkscape in to Visicut
* Dedicated PC for control, should be a nice friendly environment as well. Possibly a custom X desktop with only the required tools visible?
* LaOS on the control board to start with, later to be worked on for more functionality
* Monitor arm and suspended keyboard/trackball (kindly donated by Jon) to take up less worktop space
* Alignment controls on the device as well as in PC software
* View of all internal cameras
