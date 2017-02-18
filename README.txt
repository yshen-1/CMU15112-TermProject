Project Description:
This project processes an audio .wav file and writes the timestamps associated
with the beats in the file into the text file beats.txt.
When the processing is finished, the player is given the option to play a bubble
popping game. Bubbles are generated when the game time matches a beat timestamp
in 'beats.txt', and consist of an approximation of the audio waveform at the
time of bubble formation and the player's approximation. To pop the bubbles,
the player must guess at the amplitudes associated with each frequency
component used in the audio waveform approximation using the sliders on the left
that appear when a bubble is selected. The score is incremented by 100 for
each bubble popped.
 
Installation Instructions:
1. Install dependencies included in the "Required Libraries" folder.
2. Place the termProject.py game file and the beats.txt file together in
a directory. (unzip the gameFiles.zip for beats.txt)
3. Place a .wav file in that directory and process it to fill beats.txt.
4. Play the game.