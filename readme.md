# Ticket To Ride: Europe LUA repository for TTS
Please bear in mind this is my first attempt at a mod on Tabletop Simulator altogether.

I used [ButtonVisualizer](https://steamcommunity.com/sharedfiles/filedetails/?id=965795906&searchtext=button+visualizer) by GiantDwarf01 to easily setup the buttons which is why they're bound to the Kraken table, (same for the code that controls the game). If someone has suggestions about how to better structure this project, I am accepting pull requests and suggestions.

Currently, this script handles the following actions:
- Automatic game setup
- Grab/replace cards automatically from the shared pool
- Grab 1/Grab 2 functionality from the deck.

My further plans are to add the following features:

- Automatic train placement system.
- Automatically discard cards used when building a train route via the above automation.
- Automatic scoring system (except for routes, that sounds hard).
- Auto-shuffling when the train cards are about to run out.
- More error validation if things are done out of order or if certain decks can't be found in scripting zones.
- Potentially creating my own turn tracker as Tabletop Simulator API does not have a way to forcefully end turns yet, I'd like to automatically force a players turn to end after completing their available actions.