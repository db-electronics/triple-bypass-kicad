# Triple Bypass Version 2
This is a redesign of the fantastic 3bp from dbElectronics.  The goal was to redesign the board to accommodate all models on one pcb without the need to swap parts. It was a team effort between myself, Retrorgb, and Jose Cruz who did the majorty of the testing. Ace, FirebrandX and Mobiusstriptech all were part of the group that helped with the redesign and added various ideas and suggestions that lead to the final product.  The audio adjustment work was done with the help of the mdFourier tool by Artemio Urbina found here - 
https://github.com/ArtemioUrbina/MDFourier.  Artemio and Bfbii stayed up many late nights and helped me run mdFourier to get the levels to match as close as we could to a model 1 va3 genesis.


http://www.sega-16.com/forum/showthread.php?31989-Take-your-Genesis-audio-to-the-next-level-The-Mega-Amp-2-0-is-here!

# Confirmed Working
The current version of this is working with no issues and has been tested and measured with mdFourier. 

# Design Files
I designed this used Easyeda and while I have made the file open for people to edit I have not yet been able to allow for the files to be truly open source.  this is a work in progress and if i have to remake everything from scratch in Kicad.

# Change Log
 - Added jumpers so that all pulldowns could be enabled or disabled with out switch parts.
 - Added AC coupling capacitors on the input of the ths7374 to accommodate for systems that have not been measured yet.
 - Change the op amp to a soic8 footprint to accommodate a larger variety of possible op amps.
 - Changed the op amp to a tl972 low noise op amp.
 - Lowered the overall volume and increased resistance to try and alleviate some of the clipping in the louder games.
 - Changed the resistor values and numbering to try and fit on the smaller board.
 - Changed audio and video capacitors to tantalum to accommodate for a bottom mount. 
 - Adjusted and tested installation in a model 1 Genesis. 
 - Increased the audio output capacitors to 47uf.
 - Shrunk the overall size and move the din to the middle of the board to try to avoid the power jacks on a bottom install. 
 - Changed the Low pass filter to a solder jumper that will enable when it is jumped.
