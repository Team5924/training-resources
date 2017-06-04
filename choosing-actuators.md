# choosing actuators

types of actuators

* motors
* pneumatic cylinder
* rotary pneumatic actuator
* linear actuator
* pwm servo
* solenoid
 

We have different kinds of actuators available. Each actuator is suited for a different use case. Pneumatics are generally simpler than a motor. Usually a motor will require gearing to accomplish a task. FRC motors are high rpm low torque by default. 
 
## position control
There are a few ways to achieve position control of a mechanism. If limited positions are needed, pneumatics with hard stops is a simple way to accomplish this. For arbitrary positions, a motor is a good solutions. The motor is more complicated however because it will require a sensor and a control loop. 
 
## pneumatics vs motors

### advantages of pneumatics
* can reduce load on battery (especially if tank charged before match)
* simple software control
* fast and powerful
* can’t damage by stalling
* can be lighter if the system is in place anyway
* no limit like the pdp slots for motors
 
### disadvantages of pneumatics
* limited positions (usually 2)
* have to maintain another system on top of the electrical part of the control system
* possible danger
 
### advantages of a motor
* arbitrary position control
* can package better
 
### disadvantages of a motor
* control loop
takes a limited pdp slot
increases battery load
can stall and break
 
## rules of thumb
* An electric actuator is almost always the better choice if no pneumatic system is present as maintaining a pneumatic system for one mechanism would likely outweigh the benefits of using pneumatics.