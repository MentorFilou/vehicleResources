## What is this?
This is an example documentation of an add-on vehicle in alt:V multiplayer.

# How to Setup
1. Copy the "vehicle" folder into your "resources" folder ('.../altv-server/resources/'). 
2. Rename it to anything you want (ex.: manufacturer_modelname or lspd_pack).
3. Delete the example '.meta' file in 'stream/'.
4. Delete every example '.yft' and '.ytd' files 'stream/assets/assets' and "stream/assets/mods'.
5. Delete the example '.datxx' file in 'stream/audio'.
6. Delete the exanple '.awc' file in 'stream/audio/sfx'.
7. Copy-Paste the '.yft' and 'ytd' files which are for the base models from your add-on vehicle into 'vehicle/stream/assets/assets'.
8. Copy-Paste every '.yft' file which you did not used in step 6 into 'stream/assets/mods'.
'vehicle/stream/assets/mods'.
9. Copy-Paste every '.dat-' file ('.dat10', '.dat10.nametable', '.dat10.rel', '.dat54', '.dat54.nametable', '.dat54.rel', '.dat151', '.dat151.nametable' & '.dat151.rel') into 'stream/audio'.
10. Copy-Paste the '.awc' files into 'stream/audio/sfx'.
11. Remove every mentioned file on the 'stream.cfg' which was not included in this add-on vehicle.
12. Add the folder name (base: 'vehicle') to the 'server.cfg' as a resource.

Now this vehicle should just work all fine for you.

## Infos
- The 'dlctext.meta' is never mentioned in the 'stream.cfg'.
- The meta files are mentioned as them.
- The audio sfx files are mentioned as their folder.
- The other audio files are mentioned grouped as '.dat' for every different type of them. They are most likely named like you can see in 'examplefiles/stream/audio' with '_amp', '_game' & '_sounds'.
- The folder structure is just an example.

## Use it as a template...
A good advice might be to have a template folder. Therefore just do step 1, but then name it something like '.vehicles', '!exampleveh', '#veh' or '_vehicletemp'. (The signs will list this template folder in top of your resources.) Now do steps 3 to 6. Your template folder is done. From now on you just have to copy your tempkate name it as you want and do steps 7 to 12.
