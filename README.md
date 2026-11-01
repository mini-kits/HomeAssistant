# Home Assistant automations and code
Various files that I have created for my Home assistant setup.

Development Sendspin code for the ESP32 A1S Audio Module.  Lots of changes to fix audio plops and ticking noise from the speakers.

Sendspin Rev1.7 is the latest and fixes a number of issues with audio muting and noise by adding delayed audio from the i2s output and also sequencing of the mute switch GPIO21.  

The noise is still not fully fixed and when paused some very low noise is heard every few seconds.  I think due to the limits of the ESP32-A1S layout and design there is no actual way of fully fixing this issue, although it was not a problem when used with Squeezelite. 

A Static Delay Adjustable has also been added so that Music Assistant can show a Delay slider for sendspin players to accurately time different speakers that can have internal DSP with that causes a delay.
