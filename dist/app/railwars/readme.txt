RailWars!!

by Tharger

RailWars is a modification for Quake3 that changes all the weapons in the game to the railgun.  A player starts with the rail and infinate ammo, and can't pick anything else up.  Accuracy and hit streaks are logged, and the server can change how much damage the rail does.  This works with any map, any gametype, and the bots.

Enjoy!

INSTRUCTIONS:
To install, unzip this to your Quake3 directory, making sure that "use folder names" is checked on.  For example, if you have Quake3 installed to "c:\Program Files\Quake III Arena\", unzip it to there.  The zip file should do the rest.

To play you MUST use the command line option of "+set fs_game RailWars" when you start Quake3.  An easy way to do this is use the RailWars.bat file that was put in your Quake3 directory.  If you don't want to do that, you can go to "start", "run", click "browse", find your Quake3 executable, and then append "+set fs_game RailWars" to the end of it (without quotes!!)

If you encounter problems or have other comments, please email scottn@ufl.edu

Visit http://tharger.quakecity.net for more stuff from Tharger

Note to server admins:  You MUST have sv_pure set to 0 (type \sv_pure 0 in the console) for this to work properly.  You can change how much damage the rail does by typing \raildamage ### at the console, where ### is how much damage you want it to do.  100 is the default...try something like 1000 to make every shot kill.