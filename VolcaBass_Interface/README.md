# VolcaBass_Interface

Max4Live KORG Volca Bass interface. 
<br/>

![](https://github.com/tfari/M4L-Projects/blob/main/VolcaBass_Interface/volcabass_interface_interface.png)
<br/>

Implements controls so as to provide a ground for midi programming.

**Place before an External Instrument.**

Controls are color coded:

* Blue tinted controls are display only. 
* Yellow tinted controls are modulable.  
* Red tinted controls are internal to the device.  

All modulable controls have two circle buttons:

* One _**RED**_, for randomizing the value.
* One _**BLUE**_, for resetting the controls to their default values.

_**Every section has a RANDOM/DEFAULT pair of buttons, which does respectively for the whole section.**_

The VCOs controls have three modes (and respective sliders):

* _**ST:**_ which constrain the control to semitone changes.
* _**C:**_ which constrains the control to cents changes.
* _**BOTH:**_ which holds the full width of the pitch controls. 
* _**Whichever mode is selected, only that slider works.**_

There are 4 random buttons in the CTRLS section:

* _**Random**_ randomizes every modulable control.
* _**Random Ctrl**_ randomizes everything but the VCOS.
* _**Random VCOS**_ does the opposite. 
* _**Total Random**_ randomizes everything plus the display-only ones. This is useful to, for example, come up with entirely new patches.
