# Cave Helicopter Flash Game
Welcome to the github repo for an extremely stupid LabVIEW game that I made during a training course a few years ago.
Remember [this game](https://www.addictinggames.com/clicker/helicopter-game) from the early 2000s? 
Would you like to play a version that uses more system resources, has significantly worse graphics, includes confusing and poorly implemented gameplay features and is just completely unnecessary?
Would you like to play that version...IN LABVIEW???
Of course you would!

## Installation and Testing
* Tested on LabVIEW 2017 on Windows 10
* Requires [NI Vision Acquisition Software](https://www.ni.com/en-gb/support/downloads/drivers/download.vision-acquisition-software.html)
* May also require [NI Vision Development Module](https://www.ni.com/en-gb/support/downloads/software-products/download.vision-development-module.html)???
* Open `helicopter.vi` and press the run button in the toolbar...a baptism by fire is the best way to learn how to play this stupid stupid game! Basically press the large button and try not to LOL when you crash if you are playing at work. Hit CTRL-E to quickly bring up the block diagram in case your boss walks by!

## Known Issues
* The high scores list is stored as a local text file (LOL) so if anyone has any suggestions on how to implement a global high scores list I would welcome them
* Single fuel parcels show up as two separate graphical objects and I have NO IDEA WHY
* I would love to compile this as a standalone .exe file so people can play it without having to have LabVIEW installed on their computer but...I haven't gotten around to it yet
