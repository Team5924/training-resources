# can bus

CAN stands for controller area network. The can bus is a multi master bus that was designed for the automotive industry.

learn more about can [here](https://en.wikipedia.org/wiki/CAN_bus)
 
## can bus in frc

### compatible control system components
* speed controllers (e.g. talon srx)
* pcm
* pdp
* roborio
 
We use the can bus on FRC robots to enable communication between the pcm, pdp, roborio, and speed controllers. CAN offers many benefits over PWM (pulse width modulation) in the control system. These benefits include daisy chaining and transmitting far more information.

### topology

recommended topology is a single line with terminating resistors at both ends (which both the roborio and pdp have)

[relevant chief delphi thread](https://www.chiefdelphi.com/forums/showthread.php?t=132323)

### best practices

* use twisted pairs between nodes
