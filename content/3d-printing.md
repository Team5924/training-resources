# 3d printing
 
our main 3D printer is an Ultimaker 2+
 
## materials
We mainly use PLA and PETG. PLA is easy to print but not as resilient as PETG. PETG can be more difficult to print because it likes to stick aggressively to the bed and pull chunks out of the glass. It also has a narrower window for ideal settings than PLA. 

see Thomas Sanladerer's [filaween series](https://www.youtube.com/playlist?list=PLDJMid0lOOYl8TZJV9xHznKFq5yA5ZTi2) for in depth experimental comparison of filaments

### poly lactic acid (PLA)
pla is good for parts where strength and temperature resistance aren't a concern. 

### polyethylene terephthalate glycol-modified (PETG)
petg is a good go-to for robot parts. it has a glass transition temperature compared to pla. 

## slicer
Cura is the slicer we use. it can be [downloaded from Ultimaker’s website](https://ultimaker.com/en/products/cura-software). the [source](https://github.com/Ultimaker/Cura) is availble on Ultimaker’s github. the slicer's job is to turn our model into instructions the printer can understand and execute in a format called gcode.

## nozzles

### orifice size
Different nozzle orifices are used for different purposes. For finer prints, use a smaller nozzle. Generally we use a 0.8mm nozzle for faster print times. Thicker layers will be stronger than thinner layers which is another advantage of using a larger nozzle. A good rule of thumb for max layer height with a given nozzle is 80% of the nozzle’s orifice. For example, a 0.8mm nozzle would have a max layer height of 0.64mm.

### material
nozzles come in different materials. brass is the default for its low cost, good thermal conductivity, and durability for the usual materials. hardened nozzles should be used when printing particularly abrasize filaments, such as carbon fiber. the abrasive filament can wear away a regular brass nozzle easily and increase the effective orifice of the nozzle affecting your prints. hardened nozzles are more resistant to the abrasion and thus last longer.

## getting started
* get a mesh file, probably from your cad software (stl is common)
* onshape export instructions
* import the file into cura
* select the appropriate settings
* put sliced gcode onto sd card with a memorable and descriptive name
* put sd card in ultimaker and print

## troubleshooting

### print won't stick to the bed
things to check

* z offset is set correctly. the nozzle may be starting too close or too far away from the bed
* if the bed isn't level, some parts of the first layer may not adhere as well as others causing the part to lift
* bed should be cleaned with alcohol or acetone
* bed may need to be coated with gluestick or another solution for certain materials

### filament isn't coming out
things to check

* there is material on the spool and it isn't tangled
* try the [atomic method](https://ultimaker.com/en/resources/149-atomic-method)
* extruder tension
* extruder hobbed gear 

## printers in the lab
### Ultimaker
#### maintenance

The Ultimaker requires occasional maintenance. Here are some things to check every once in awhile:

* proper belt tension
* linear rods are seated properly in housing
* motion system is properly lubricated
* bed is clean & level
* nozzle is clean

### tommy
tommy is a makerbot thing-o-matic retrofitted with new parts

## external resources

### [Thomas Sanladerer's Tom's Guides playlist](https://www.youtube.com/watch?v=pRX_uvG9Z-w&list=PLDJMid0lOOYnRCAdbFfzECor3EbqF8euw) 