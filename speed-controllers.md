# speed controllers

frc speed controllers communicate via can or pwm

## types

for most applications, the speed controller you use won't make a big difference as long as you choose a reliable one. the talon srx, victor sp, and spark have all been reliable in our experience.

### talon srx

the [talon srx](http://www.ctr-electronics.com/talon-srx.html) is a can based speed control. it has many "smart" features, such as onboard pid control. pwm can also be used to control a talon srx. the talon srx features built in wires. this can be good or bad. it 's good in situations where you want to just add a connector quickly. it's bad when the wire gets so short that the speed controller is useless without opening its casing and replacing the wire.

### victor sp

the [victor sp](https://www.vexrobotics.com/217-9090.html) is made by vex and comes in a form factor similar to the talon srx.  like the talon srx, the victor sp has wires built in. an advantage to the victor sp is its relatively small form factor.

### spark

the [spark](http://www.revrobotics.com/spark/) is made by rev robotics. it's basic and cheap, offering the same funionality as the victor sp along with limit switch input.