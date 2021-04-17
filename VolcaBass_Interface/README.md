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

* One RED, for randomizing the value.
* One BLUE, for resetting the controls to their default values.

**Every section has a RANDOM/DEFAULT pair of buttons, which does respectively for the whole section.**

The VCOs controls have three modes (and respective sliders):

* ST, which constrain the control to semitone changes.
* C, which constrains the control to cents changes.
* BOTH, which holds the full width of the pitch controls. 
* **Whichever mode is selected, makes the value in the respective slider count.**

There are 4 random buttons in the CTRLS section:

* "Random" randomizes every modulable control.
* "Random Ctrl" randomizes everything but the VCOS.
* "Random VCOS" does the opposite. 
* "Total Random", randomizes everything plus the display-only ones.This is useful to for example come up with new patches.
