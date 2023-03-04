Rhythm commander is essentially a drum sequencer with some unusual features. Firstly, it has 12 patterns. Each pattern has an adjustable length, up to 64 steps. Each pattern can be sent to up to 8 channels simultaneously. Channels 1 - 4 correspond to triggers 1 - 4 on TT. 5  - 8 go to midi channels 5-8. Different patterns can be sent to the same channel, allowing you to mix and match patterns at different outputs.

Each pattern can be edited per step (xoxo style). It's possible to select a starting pattern from the DR.P and DR.T banks. Patterns are scaled over 64 steps. They can be edited after selection. Each pattern can be assign one of four different clocks, which are received at trigger in 1 - 3.  The patterns progress at the speed of the selected clock. This allows you to have multiple patterns of differing length, driven by different clocks, going to the same output/channel. Endless possibilities

Each channel can be assigned a velocity helper. For TT TR outputs, the velocity is sent to CC 1 - 4. For midi channels, velocity is sent with the midi note on command. Velocities can be scaled and given an offset. They repeat every 16 steps.

See https://docs.google.com/spreadsheets/d/1z-lZfc4HC6Y0Ka9-BgTApfB_VNcDAqefQ_KetM-Vch4/edit#gid=0 for explanation of pattern values

It requires the use of a custom firmware (included - see the .hex). This firmware enables 20 scripts but reduces the overall number of scenes. Back up your scenes if you plan to use this. Existing scenes will need to be converted to the new format before they will be compatible.

tt04s.txt is the Launcher for the midi and trigger version of the script described above. Press any light on your grid to launch into the full scene.
tt05s.txt is the main scene for the midi and trigger version of the script.

tt06s.txt is the launcher for the midi only version of the script. It has 7 output channels from 3 - 4 and 9 - 13.
tt07s.txt is the main scene for the midi only version of the script.