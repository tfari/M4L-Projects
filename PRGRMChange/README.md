# PRGRMChange

Max4Live device to change programs via Program Change controls or MSB/LSB combinations.
<br/>

![](https://github.com/tfari/M4L-Projects/blob/main/PRGRMChange/prgrmchange_interface.png)
<br/>

**Place before an External Instrument or a soft synth.**

_**PROGRAM CHANGE**_ section is self explanatory, use this if you only need to send MIDI Program Change messages.

_**MSB/LSB MODE**_ section requires a bit of a set up. 

* First you should set the MSB and LSB CC values as specified by the hardware you are using. They are set at 0 and 32 by default.

* Then, you should set up the **MSB MAX** slider to reflect the maximum max value of MSB as specified by your hardware.

* The way the _**increment**_ and _**decrement**_ buttons work , is it increments LSB by one everytime MSB does one cycle, as defined by the **MSB MAX** slider.

* The device might not reflect exactly how your hardware implements program change, so feel free to edit the device if you must, you will find the logic very easy to extend.



