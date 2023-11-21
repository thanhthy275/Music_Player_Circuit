# Music_Player_Circuit

Develop an original logic circuit in Logisim for the user interface of a 5-button music player. The interface displays the volume as an 8-LED bar graph, the track number and PLAY/PAUSE indicators (one LED for each). An interface that has:
1. a PLAY/PAUSE button
2. VOL+ and VOL- buttons
3. track skip buttons: <-(prev) and->(next)
4. 8-LED bar graph indicating 8 volume settings
5. a 2-digit decimal display, using the Logisim Hex display, that indicates the track number
6. one LED, which indicates PLAY mode is on and PAUSE mode (flashing 1Hz) OR Two LEDs, one for each mode.

Development stages:

**- Stage 1A: Implement the PLAY/PAUSE states (i.e. indicated by LED display)**

When the PLAY button is set to on, the system enters the PLAY state:
the PLAY LED is turned on
the PAUSED LED is turned off.
When the PAUSE button is set to on, the system enters the PAUSED state:
the PLAY LED is turned off
the PAUSED LED is turned on.
When the PLAY button is set to off
the PAUSE button has no affect on the system state.


**- Stage 1B: Implement PAUSE-to-PLAY transition** 

When the music player is in the PAUSED state if the PAUSE button is pressed it will return to the PLAY state if it was in a PLAY state prior, otherwise it has not affect on the PLAY state.


**- Stage 2: Implement volume control and display**


In either PAUSED or PLAY states, the volume can be adjusted, and the current volume level visible on the display.

**- Stage 3: Implement track skipping and display**

Demonstrate that track skipping can be performed in either PAUSED or PLAY states, and the current track displayed in either state.


**- Stage 4: Implement an OFF state for your player**

Demonstrate that the music player has three states: ON (PLAY), ON (PAUSED), and OFF.


**- Stage 5A: Implement storage of previous settings for your player**

Implement storage of previous settings for your play. This should include the following:
When switched from either ON state to the OFF state, the circuit should store:
the current track number in a register (i.e. using Flip Flops)
the current volume in a register (i.e. using Flip Flops).

**- Stage 5B: Implement recall of previous player settings to initialise your player**

Implement recall of a previous player setting. This should include the following:
When switched to ON (PAUSED) from the OFF state, your circuit should recall:
the track number from registers and display this
the volume from registers and display this.

![image](https://github.com/thanhthy275/Music_Player_Circuit/assets/67629044/7a9c8dab-ea8a-4b27-9f8b-273df50360ec)
