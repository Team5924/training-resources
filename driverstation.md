# the drivertsation 
 
## driver station software
The driver station is the piece of software that communicates with the robot. The only supported OS for the driver station is Windows. The driver station is developed and maintained by National Instruments. The driver station allows for debugging robot code. Robots can connect to the driver station over wifi, ethernet, or usb.
 
## the physical driver station
The driver station can also refer to the collective parts used to run a robot. Minimally this will include a computer (usually a laptop). Driver stations generally also include a controller for a driver to move the robot around the field and another controller for another driver to manipulate the robot’s mechanisms. For example, one driver of Kendrick LOWbar used an xbox controller to navigate around the field while the other driver used a custom button board to intake and shoot balls, lower the CDF, raise the portcullis, and stow the superstructure for low bar mode.
 
![](https://lh3.googleusercontent.com/iZ_L-bHLSow5EJhnkdXd40K3rWWQ1qGsEjJ5TjN7AZzRs4EhAfotrZJunIKIVBif0jg4L-3peSZIg1s=w3360-h1724-rw)

## dashboards

The driver station can utilize a dashboard. A few different dashboards are provided. SmartDashboard is fairly basic but functional. The Labview dashboard is highly customizable and can be used without using labview for robot programming. Dashboards are useful for debugging and visualizing information. Custom dashboards can be made to communicate with the robot using NetworkTables. 
 
### dashboard projects

* [dashboard2](https://github.com/FRC3184/dashboard2)
* [SmartDashboard](https://github.com/wpilibsuite/SmartDashboard)
* [FRCDashboard](https://github.com/FRCDashboard/FRCDashboard)

### pynetworktables2js
pynetworktables2js can be used to make custom dashboards easily

## QDriverStation
 
QDriverStation is an unofficial driver station developed by an frc mentor that works on windows/mac/linux. it mostly emulates the real driver station and can be good enough depending on your needs. however, it cannot be used in competition. [Learn more here](https://frc-utilities.github.io/) or [View the source here](https://github.com/FRC-Utilities/QDriverStation)
