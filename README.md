# METALOT
METALOT is about meta modulation in 4U LW Format



Use an ST LINK to flash the unit. First the bootloader and then the METALOT.hex.

Update procedure with Parasite or Symbiote WAV file
Unplug all CV inputs/outputs from the module. Connect the output of your audio interface/sound card to the Carrier audio input (5) input. Power on your modular system with the INT. OSC (C) push-button pressed. The INT. OSC LED will blink in orange.

Make sure that no additional sound (such as email notification sounds, background music etc.) from your computer will be played during the procedure. Make sure that your speakers/monitors are not connected to your audio interface - the noises emitted during the procedure are aggressive and can harm your hearing. On non-studio audio equipment (for example the line output from a desktop computer), you might have to turn up the gain to the maximum.

When you are all set, play the firmware update file into the module. While the module receives data, the color of the ALGORITHM knob will reflect signal level - green or yellow is fine, red is too high! You can use the Carrier amplitude (D) knob to adjust the input gain.

In case the signal level is inadequate, the LEDs will blink in red. Press the INT. OSC button and retry with a correct gain. If this does not help, please retry the procedure from another computer/audio interface, and make sure that no piece of equipment (equalizer, FX processor) is inserted in the signal chain.

The calibration of the METALOT is in 2 phases:

PHASE 1:


Disconnect all CV inputs.
Hold the INT. OSC button for five seconds until the ALGORITHM knob blinks in turquoise and the oscillator state LED blinks in yellow.
Connect a patch cable to the LEVEL 2 CV input. Leave the other end of the cable unplugged.
Connect the CV output of a well-calibrated keyboard interface or MIDI-CV converter to the LEVEL 1 CV input.
Play a C2 note, or send a 1V voltage from your CV source.
Press the INT. OSC button. The ALGORITHM knob blinks in fuchsia.
Play a C4 note, or send a 3V voltage from your CV source.
Press the INT. OSC button.
Calibration is done!


PHASE 2:

Connect a constant positive voltage source (for example an ON gate signal, or the output of an offset module, or the CV from a CV/Gate interface when you play the highest note on a keyboard) to the first LEVEL CV input, and leave all the other jacks of the module disconnected.
Hold the INT. OSC button for 10 seconds until both the INT OSC and the big knob LEDs blink in red.
Disconnect all patch cables from the module.
Press the INT. OSC button. The LEDs will blink in green now. Wait for a couple of seconds.
Press the INT. OSC button again.
