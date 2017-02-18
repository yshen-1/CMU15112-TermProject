#Program Description

This program processes an audio .wav file and writes the timestamps associated
with the beats in the file into the text file 'beats.txt'.
When the processing is finished, the player is given the option to play a bubble
popping game. Bubbles are generated when the game time matches a beat timestamp
from 'beats.txt', and consist of two layers: a visualization of the audio waveform at the time of bubble formation and the player's approximation of said visualization. To pop the bubbles, the player must match his/her bubble layer with the audio visualization using the sliders on the left that appear when a bubble is selected.

#Dependency list
1. Pyaudio
2. Numpy
3. Pygame
4. Python 3

#Installation Instructions:

##Python 3
1. Go to https://www.python.org/downloads/ and download the appropriate
   installation package.

## Pyaudio
1. Run the command "pip3 install pyaudio". Administrator permission may be
   required for this step.
2. On linux, if an error regarding "portaudio.h" appears, you may wish to
   install portaudio-dev.

## Numpy
1. Run the command "pip3 install numpy". Administrator permission may be
   required for this step. For further information, consult
   https://www.scipy.org/scipylib/download.html.

## Pygame
1. Run the command "pip3 install pygame". If this does not work, you may wish to
   download and install the appropriate .whl file from
   https://www.lfd.uci.edu/~gohlke/pythonlibs/#pygame.

##Overall Program
1. Install all dependencies, as described above. Place 'background.jpg',
   'beats.txt', and 'termProject.py' in the same directory. 
2. Place the .wav file you wish to process in the installation directory.
3. Execute termProject.py and follow the instructions displayed within the
   program.

#Video demo
'project-video.txt' contains a hyperlink to a youtube video demonstrating this
program.
