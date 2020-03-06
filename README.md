# Triple Bypass Version 2
This is a redesign of the fantastic 3bp from dbElectronics.  The goal of this project was to take the initial design and accommodate all models on one pcb without the need to swap parts. It was a team effort between myself, Retrorgb, and Jose Cruz who did the majorty of the testing. Ace, FirebrandX and Mobiusstriptech all were part of the group that helped with the redesign and added various ideas and suggestions that lead to the final product.  The audio adjustment work was done with the help of the mdFourier tool by Artemio Urbina found here - 
https://github.com/ArtemioUrbina/MDFourier.  Artemio and Bfbii stayed up many late nights and helped me run mdFourier to get the levels to match as close as we could to a model 1 va3 genesis.

# Installation Instructions

Currently I suggest using the Audio installation instructions from the mega amp 2.0
http://www.sega-16.com/forum/showthread.php?31989-Take-your-Genesis-audio-to-the-next-level-The-Mega-Amp-2-0-is-here!

For rgb bypass instructions, please see https://www.retrorgb.com/genesistriplebypass.html for now. I will continue working on getting more up-to-date instructions.



# Confirmed Working
The current version of this is working with no issues and has been tested and measured with mdFourier. There are still some systems where the pull down jumpers have not been confirmed.  If you notice any issues, please let me know.
# Design Files
I designed this using the online software tool Easyeda. While I have made the file open for people to edit, I have not yet been able to allow for the files to be truly open source.  This is a work in progress and if I have to remake everything from scratch in Kicad. The files here will always be the most up to date versions. 
# Change Log 06/03/2020
- Changed the jumper settings on the silk screen to match new info from Jose Cruz that the model 2 va4 has all of the 75 ohm pulldowns on the Genesis. Nothing needs to be changed on the previous versions.  Just take note when installing in a model 2 va4.
# Change Log from V1
 - Added jumpers so that all pulldowns could be enabled or disabled without switching parts.
 - Added AC coupling capacitors on the input of the ths7374 to accommodate for systems that we have not measured or installed in yet.
 - Changed the op amp to a soic8 footprint to accommodate a larger variety of possible op amps.
 - Changed the op amp to a tl972 low noise op amp.
 - Lowered the overall volume and increased resistance to try and alleviate some of the clipping in the louder games.
 - Changed the resistor values and numbering to try and fit on the smaller board.
 - Changed audio and video capacitors to tantalum to accommodate for a bottom mount. 
 - Adjusted and tested installation in a model 1 Genesis. 
 - Increased the audio output capacitors to 47uf.
 - Shrunk the overall size and move the din to the middle of the board to try to avoid the power jacks on a bottom install. 
 - Changed the Low pass filter to a solder jumper that will enable when it is jumped.


