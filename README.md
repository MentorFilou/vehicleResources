# Find an updated Tutorial on
# **https://github.com/inofficial-altv-tutorials/vehicles**!


### en_EN
##### What is this?
This is an example documentation of how to use an add-on vehicles on the GTA V mp plattform alt:V.

#### How to Setup
1. Copy the "vehicle" folder into your "resources" folder ('.../altv-server/resources/'). 
2. Rename it to anything you want (ex.: manufacturer_modelname or lspd_pack).
3. Delete the example '.meta' file in 'stream/'.
4. Delete every example '.yft' and '.ytd' files 'stream/assets/assets' and "stream/assets/mods'.
5. Delete the example '.datxx' file in 'stream/audio'.
6. Delete the example '.awc' file in 'stream/audio/sfx'.
7. Copy-Paste the '.yft' and 'ytd' files which are for the base models from your add-on vehicle into 'vehicle/stream/assets/assets'.
8. Copy-Paste every '.yft' file which you did not used in step 7 into 'stream/assets/mods'.
9. Copy-Paste every '.dat-' file ('.dat10', '.dat10.nametable', '.dat10.rel', '.dat54', '.dat54.nametable', '.dat54.rel', '.dat151', '.dat151.nametable' & '.dat151.rel') into 'stream/audio'.
10. Copy-Paste the '.awc' files into 'stream/audio/sfx'.
11. Remove every mentioned file (meta and audio files) on the 'stream.cfg' which was not included in this add-on vehicle.
12. Rename the audio files in the 'stream.cfg'.
13. Add the folder name (base: 'vehicle') to the 'server.cfg' as a resource.

Now this vehicle should just work all fine for you.

##### Infos
- The 'dlctext.meta' is never mentioned in the 'stream.cfg'.
- The meta files are mentioned as them.
- The audio sfx files are mentioned as their folder.
- The other audio files are mentioned grouped as '.dat' for every different type of them. They are most likely named like you can see in 'examplefiles/stream/audio' with '_amp', '_game' & '_sounds'.
- The folder structure and the file names are just examples and could be different.

### Use it as a template...
A good advice might be to have a template folder. Therefore just do step 1, but then name it something like '.vehicles', '!exampleveh', '#veh' or '_vehicletemp'. (The signs will list this template folder in top of your resources.) Now do steps 3 to 6. Your template folder is done. From now on you just have to copy your tempkate name it as you want and do steps 7 to 12.



### de_DE 
##### Was ist das hier?
Es handelt sich bei diesem Repository um eine beispielhafte Vorlage zu Vehicle Add-On Resourcen auf der GTA V Multiplayer Plattform alt:V.

#### Wie nutze ich es (Setup)
1. Kopiere den "vehicle"(de: Fahrzeug) Ordner in deinen "resources" Ordner ('.../altv-server/resources/'). 
2. Bennene den Ordner, wie du willst (Bsp.: hersteller_modellname oder polizei_pack).
3. Lösche die beispielhafte '.meta' Datei im Ordner 'stream/'.
4. Lösche die beispielhaften '.yft' und '.ytd' Dateien in den Ordner /stream/assets/assets' ud "stream/assets/mods'.
5. Lösche die beispielhaften '.datxx' Dateien in dem Ordner 'stream/audio'.
6. Lösche die beispielhaften '.awc' Dateien in dem Ordner 'stream/audio/sfx'.
7. Kopiere die '.yft' und 'ytd' Dateien, die für die Models sind (meistens benannt, wie der Spawnname) aus deinem Add-On Fahrzeug in den Ordner 'vehicle/stream/assets/assets'.
8. Kopiere jede '.yft' Datei, die noch nicht in Schritt 7 genutzt worden in den Ordner 'stream/assets/mods'.
9. Kopiere jede '.dat' Datei ('.dat10', '.dat10.nametable', '.dat10.rel', '.dat54', '.dat54.nametable', '.dat54.rel', '.dat151', '.dat151.nametable' & '.dat151.rel') in den Ordner 'stream/audio'.
10. Kopiere die '.awc' Dateien in den ordner 'stream/audio/sfx'.
11. Entferne jede Zeile, die eine Datei erwähnen, die in deinem Fahrzeug nicht dabei war, aus der 'stream.cfg'.
12. Korrigiere die Namen der Audio-Dateien in der 'stream.cfg'.
13. Füge den Ordner (, der am Anfang: 'vehicle' hieß,) zu der 'server.cfg' als Resource hinzu.

Das Fahrzeug sollte jetzt auf deinem Server spawnbar sein.

##### Infos
- Die Datei 'dlctext.meta' wird in der 'stream.cfg' nie erwähnt, da sie immer dabei ist.
- Jede '.meta' Datei wird in der 'stream.cfg' einzeln erwähnt.
- Die Audio Dateien, die im Ordner 'stream/audio/sfx' gelandet sind, werden nicht einzeln, sondern als Ordner in der 'stream.cfg' erwähnt.
- Die anderen Audio Dateien, werden gruppiert als '.dat' für jede verschiedene Zahl hinter diesem '.dat' erwähnt. Sie heißen auch meistens in der Endung alle entweder '_amp' oder '_game oder '_sound'.
- Die Ordnerstruktur und Namen sind nur beispielhaft und könnten natürlich mit etwas Aufwand umbenannt werden.

### Nutzung als Vorlage
Ich empfehle euch, dass ihr euch einen Vorlageordner für Fahrzeugresourcen macht. So könnt ihr schneller neue Fahrzeuge hinzufügen. Dafür solltet ihr einfach Schritt 1 machen (Ordner kopieren) und den Ordner dann sowas wie '.vehicles', '!exampleveh', '#veh' oder '_vehicletemp' nennen. (Die Sonderzeichen vor dem Namen sollen den Ordner ganz oben listen.) Wenn ihr jetzt die Schritte 3 bis 6 macht, habt ihr eine fertige Vorlage. Ab sofort müsst ihr den Ordner nur noch kopieren, umbennen wie ihr wollt und könnt mit den Schritten 7 bis 12 ein neues Fahrzeug hinzufügen.


## Credits
- Rockstar Games (Grand Theft Auto V) -> https://www.rockstargames.com
- multiplayer plattform alt:V -> https://altv.mp/#/

=> btw, here is alt:V's official tutorial for this -> https://wiki.altv.mp/wiki/Tutorial:Stream_Vehicles
