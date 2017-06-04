# control system
 
## standard components
* battery
* breaker
* power distribution panel (pdp)
* roborio
* voltage regulator module (vrm)
* pneumatic control module (pcm) (only needed if using pneumatics)
* radio
* speed controllers
* robot signal light (rsl)

## overview

![](http://team358.org/files/programming/ControlSystem2015-2019/images/2016_CS_Layout.jpg)

Power distribution starts with the battery. We use 12V batteries. From the battery, power flows to the PDP where the positive termination from the battery to the PDP is broken by the main breaker. This is the on/off switch for the robot as well as a safety mechanism. The PDP then distributes power to the rest of the control system. The PDP has special designated ports on the bottom for the roborio, vrm, and pcm. The other ports are general purpose, with 8 being 40A slots and another 8 being 30A or 20A slots. Usually speed controllers occupy these ports. The drivetrain will generally be on 40A slots because it will generally pull the most current. The radio gets its power from the 12V 2A VRM port. The VRM regulates power from the PDP to provide steady 12V and 5V outputs. The PCM gets power from the PDP and communicates with the control system over the CAN bus. The roborio’s power also comes from the pdp, and it can communicate with the control system over can, serial, i2c, pwm, and other methods. Speed controllers communicate with the roborio over can or pwm. The RSL (robot safety light) is powered and controlled by the roborio rsl port. The roborio and radio communicate via an ethernet cable. The radio can optionally connect to other components such as an IP webcam. The radio then allows for communication with the driver station via a laptop.

## roborio

the roborio is the brain of the control system. it's made by National Instruments. it's IO includes: PWM, CAN, RS232, USB, analog input, DIO, ethernet, I2C, SPI, and MXP.

see the [roborio manual](http://www.ni.com/pdf/manuals/374474a.pdf) for more info

## external resources

* [screenstepslive](https://wpilib.screenstepslive.com/s/4485/m/24166)