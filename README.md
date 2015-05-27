# partroxis
Galaban's Partroxis Plugin

This plugin provides "guides" through the Partroxis maze.  When you enter a
room in the maze, the guide will provide the correct direction.  If multiple
directions exist, the guide will show you the two possibilities.  If you choose
wrong, the next time you enter the room, that exit will not be shown.

There is also a speedwalk function that will return you to the last correct
room in the maze:  "partroxis return"

   BY DEFAULT, these guides are not enabled. You will not receive any help.
Re-enter the area or use "partroxis guide" to turn the guides on.

Commands available:

partroxis help           -- this help screen

partroxis autohunt <mob> -- run to the mob within the maze

partroxis guide          -- Enable the maze guides

partroxis return         -- return to the last explored room in the maze

partroxis reset          -- reset the internal cache.

INSTALL

To add this to the MuschClient, just download the Galabans_Partroxis_Plugin.xml file and drop it into your Mushclient's "plugin" directory. Restart your MushClient and it will load.
