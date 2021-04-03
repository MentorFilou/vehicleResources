## What is this?
This is an example documentation of an add-on vehicle in alt:V multiplayer.

# How to Setup
1. Copy the "vehicle" folder into your "resources" folder ('.../altv-server/resources/'). 
2. Rename it to anything you want (ex.: manufacturer_modelname or lspd_pack).
3. Delete the example '.meta' file in 'stream/'.
4. Delete every example '.yft' and '.ytd' files 'stream/assets/assets' and "stream/assets/mods'.
5. Delete the example '.datxx' file in 'stream/audio'.
6. Delete the exanple '.awc' file in 'stream/audio/sfx'.
6. Copy-Paste the '.yft' and 'ytd' files which are for the base models from your add-on vehicle into 'vehicle/stream/assets/assets'.
7. Copy-Paste every '.yft' file which you did not used in step 6 into 'stream/assets/mods'.
'vehicle/stream/assets/mods'.
8. Copy-Paste every '.dat-' file ('.dat10', '.dat10.nametable', '.dat10.rel', '.dat54', '.dat54.nametable', '.dat54.rel', '.dat151', '.dat151.nametable' & '.dat151.rel') into 'stream/audio'.
9. Copy-Paste the '.awc' files into 'stream/audio/sfx'.
10. Add the folder name (base: 'vehicle') to the 'srver.cfg' as a resource and start the server.
