## cnc
 
a cnc is ideal for situations where you need a high precision parts and/or lots of them, like gussets. Some cnc machines are only for wood and plastics while others will do metals. The 6040 cnc in the lab will machine aluminum as well as woods and plastics. CNC routing is a subtractive process (as opposed to 3d printing which is additive).
 
## workholding
Sheet material can be held down to a spoilboard with screws. Box tubing should be clamped in vises and be supported in multiple locations.
 
see [this image](http://i.imgur.com/cCq499Tl.jpg) for an example of holding tubing properly
 
## spoilboard
MDF makes for a good spoil board. Before use, it should be faced by milling away a thin layer from the top. This ensures a flat and parallel surface. After extended use, the spoil board should be faced again.
 
## software

### cam
cam stands for computer aided machining. it's what turns our designs into instructions the cnc machine understands and executes. since you can't just put a dxf or step file into your cnc, the cam software is what stands between the design software and the cnc.

[cambam](http://www.cambam.info/) is a simple application for making instructions the cnc machine can understand
 
### host software
* [pronterface](http://www.pronterface.com/)
* [cncjs](https://github.com/cncjs/cncjs)

## getting started
* export dxf from cad software
* import dxf into cambam
* assign operations
* export gcode
* import gcode into host
* set origin
* turn on spindle
* run gcode

## external resources
* [smoothieware wiki](http://smoothieware.org/cnc-mill-guide)
* [CNC Routers for FRC Robotics](https://www.chiefdelphi.com/forums/showthread.php?t=158505)