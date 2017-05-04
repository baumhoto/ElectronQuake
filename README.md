# ElectronQuake

**ElectronQuake** is fork of WebQuake which is an HTML5 WebGL port of the game Quake by id Software. 

WebQuake will run inside Electron, so no Http-server is required.

#Usage

1. npm install electron -g  # install electron globally
2. npm install
3. You need the quake data files (shareware or commerical)
4. Copy the `id1` folder from the Quake folder to the Client/ folder (where index.htm is located)
5. If you're running a system with case-sensitive names (such as Linux), make sure that all game files **except for code files** have lowercase names.
6. electron index.js  # will start electron and show the quake-console
7. +mlook #enter to enable mouse-look
8. either press ESC or enter: *map start* to load a level

# Tips

If the sound randomly doesn't play, go to console (press ~ or Options > Go to console in main menu), type `stopsound` and press Enter.

You can delete saved games by pressing Del in the load or save menus. This only works for the saved games created in WebQuake.