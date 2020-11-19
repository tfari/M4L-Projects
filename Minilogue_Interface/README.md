# Minilogue_Interface

Max4Live KORG Minilogue interface. 
<br/>

![](https://github.com/tfari/M4L-Projects/blob/main/Minilogue_Interface/minilogue_interface.png)
<br/>

Implements controls for every knob and switch so as to provide a ground for midi programming.

Place before an External Instrument.

"Reset" resets the device to default values, "Dump" sends the value of all controlls to the minilogue. The small round buttons besides some knobs are to reset the knob to central values, mostly pitches, etc.
"Random" randomizes all parameters, small red buttons near some of the controls serve to randomize those parts only: 

 
 * VCO 1 
 * VCO 2 
 * VCO OPTIONS(CROSSMOD/PITCH EG/SYNC/RING)
 * MIXER
 * FILTER
 * ENVELOPES
 * LFO
 * DELAY
 * VOICE MOD. DEPTH

**Warning:**

Having automated knobs moving around makes moving knobs by hand not registered by the minilogue. You have to pause the reproduction and move the knob. (Use the "Dump" button if it stills doesn't update).

