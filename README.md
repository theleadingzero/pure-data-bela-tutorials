# Pure Data Bela Tutorials
A collection of Pd abstractions and patches for learning how to program Bela with Pure Data. They build up an interactive project that uses analog sensors to trigger audio sample playback and control audio effects.

See [embelashed.org](http://embelashed.org) for more thorough documentation.

## How to Use
Examples 1-4 are to be run on a laptop running Pure Data. Try changing what audio file is played (look through the samples folder for other options) and changing the trigger threshold.

Examples 5 and above are to be run on a Bela board with analog sensors attached.

Each example largely builds on the previous one, introducing how to interact with the different objects.

## Installation

To run the example patches in Pure Data on your computer, add the path of the 'abstractions' folder to the Pd -> Preferences -> Path...

To run on a Bela board:
* either copy the needed abstractions to the local project folder, 
* or scp the abstractions folder to `~/Bela/Projects/pd-externals/`


## Credits
Patches and audio design by Andrea Guidi and Robert Jack. Further edited and added to by Becky Stewart.

See [the Bela website](http://bela.io) for more information about working with the Bela board.