# pneumatics

"the branch of physics or technology concerned with the mechanical properties of gases"


## pneumatics in an FRC robot

The pneumatic system starts with a compressor. The compressor compresses air up to 120 psi. The pressure switch and pressure relief valve ensure the system doesn’t exceed 120 psi for safety reasons. The air is stored in air tanks. Gauges are used to monitor air pressure at various points in the pneumatic system. The regulator is used to regulate the air pressure to an FRC legal pressure of 60psi. A manifold is used to efficiently distribute air to the solenoids. Solenoids control the direction of airflow by allowing or blocking airflow in certain directions. Solenoids enable us to control pneumatic actuators. The PCM (pneumatic control module) allows us to control the solenoid and compressor.

![](https://i2.wp.com/roboaztechs.org/wp-content/uploads/2014/09/PneumaticsDiagram1.jpg?resize=701%2C416)

## components
components you'll find in the pneumatic system. each is linked to an external resource with more info

* [compressor](http://www.popularmechanics.com/home/how-to/a151/how-air-compressors-work/)
* [solenoids](http://mechatronics.mech.northwestern.edu/design_ref/actuators/solenoids.html)
* storage tanks
* gauge
* [pressure sensor](https://www.andymark.com/product-p/am-3219.htm)
* [regulator](https://en.wikipedia.org/wiki/Pressure_regulator)
* [manifold](https://en.wikipedia.org/wiki/Manifold_(fluid_mechanics))
* fittings
* [pressure relief valve](https://en.wikipedia.org/wiki/Relief_valve)
* [pressure switch](Pressure_switch)
* [pcm](http://www.ctr-electronics.com/pcm.html)
* [actuators](http://mplab.ucsd.edu/tutorials/Pneumatics.pdf)

### pcm

The pneumatic control module is our interface between the air and electrical system. The pcm contains several relays to direct power to the compressor and solenoids which in turn cotrol air flow. The pcm communicates with the roborio over the can bus. The pcm is powered through a special port on the pdp. The pcm can accomodate 12V or 24V solenoids (selectable via the VSOL jumper). CTRE makes the pcm.

[pcm user's guide](http://www.ctr-electronics.com/PCM%20User's%20Guide.pdf)

![](images/pcm.jpg)

## fittings

there are several types of fittings for the pneumatic system

see [this image](http://img.diytrade.com/cdimg/819313/24261315/0/1324276319/Pneumatic_fittings.jpg) this image for a comprehensive list.

## suppliers

* andymark (clippard tanks, pressure sensor)
* vexpro (fittings, manifold, solenoids)
* ctre (pcm)
* mcmaster (actuators)

## external resources

* [pneumatics for newbies by FRC team 358](http://mechatronics.mech.northwestern.edu/design_ref/actuators/solenoids.html)