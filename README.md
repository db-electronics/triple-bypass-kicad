# Triple Bypass Verison 2
This is a redesign of the fantastic 3bp from dbElectronics.  The goal was to redesign the baord to accomidate all models on one pcb without the need to swap parts. It was a team effort between myself, Retrorgb, and Jose Cruz who did the majorty of the testing. Ace, FirebrandX and Mobiusstriptech all were part of the group that helped with the redesign and added various ideas and suggestions that lead to the final product.  The audio adjustment work was done with the help of the mdFourier tool by Artemio Urbina found here - 
https://github.com/ArtemioUrbina/MDFourier.  Artemio and Bfbii stayed up many late nights and helped me run mdFourier to get the levels to match as close as we could to a model 1 va3 genesis.


http://www.sega-16.com/forum/showthread.php?31989-Take-your-Genesis-audio-to-the-next-level-The-Mega-Amp-2-0-is-here!

# Confirmed Working
The current version of this is working with no issues and has been tested and measured with mdFourier. 

# Design Files
I desiged this used Easyeda and while I have made the the file open for people to edit I have not yet been able to allow for the files to
be truely opensource.  this is a work in progress and if i have to remake everything from scratch in Kicad.

# Change Log
 - Added jumpers so that all pulldowns could be enabled or disabled with out switch part.s
 - Added AC coupling capicitors on the input of the ths7374 to accomidate for systems that have not been measued yet.
 - Chanage the op amp to a soic 8 footprint to accomidate a larger variaty of posible op amps.
 - Changed the op amp to a tl972 low noise op amp.
 - Lowered the overall volume and increade resistance to try and aliviate some of the clipping in the louder games.
 - Changed the resistor values and numbering to try and fit on the smaller baord.
 - Changed audio and video capicitors to tantalum to accomidate for a bottom mount. 
 - Adjusted and tested instalation in a model 1 Geneis. 
 - Increased the audio output capicators to 47uf.
 - Shrunk the overall size and move the din to the middle of the board to try and aviod the power jacks on a bottom install. 
 - Changed the Low pass filter to a solder jumper that will ineable when it is jumped.
