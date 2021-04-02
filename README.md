# What is this?
This gives an example for how to add add-on vehicles as a resource to
your alt:V server and documents all the stuff which can possibly be an
add-on vehicle resource. This of course gives an overview as detailed
as possible.

# Prologue
"How to Setup" and "Descpription" might seem a bit difficult, but as said
above this gives an overview as detailed as possible. Following the
#HowToSetup a few times it will get a routine for you and then this will
be much easier. The documentation of the included file types
(#AdditionalInformation) also is not as simple, but this is also not
necesarry to know.

# How to Setup
1. Copy the "vehicle" folder into your "resources" folder
('.../altv-server/resources/'). 
2. Rename it to anything you want (ex.: MANUFACTURER_MODEL).
3. Delete every example '.meta', which was not included in the add-on vehicle
you are adding.
4. Copy-Paste every '.meta' file from your add-on vehicle into 'vehicle/stream'.
5. Delete every example '.yft' and '.ytd' file 'vehicle/stream/assets/assets'
6. Copy-Paste the '.yft' and 'ytd' files from your add-on vehicle, which are
most likely named like the vehicle is named (filled in mostly into 'NAME' in
this repository) or very similiar if this is a vehicle pack (smth like 'NAMEa',
'NAMEb', etc.) into 'vehicle/stream/assets/assets'.
7. Delete every example '.yft' file in 'vehicle/stream/assets/mods'.
8. Copy-Paste every '.yft' file which you did not used in step 5 into
'vehicle/stream/assets/mods'.

# Additional Information
#### main design and tuning (design)

'.yft' files in 'vehicle/stream/assets/assets'

-> ? (base)

'.ytd' files in 'vehicle/stream/assets/assets'

-> ? (probably texture related base as it is a '.ytd')

'.yft' files in 'vehicle/stream/assets/mods'

-> extended tuning stuff for this vehicle (liveries, spoilers, ...)

#
### audio files

'.awc' files in 'vehicle/stream/audio/sfx/dlc_NAME'

-> ?

'_awp.dat10' files in 'vehicle/stream/audio'

-> ?

'_sounds.dat54' files in 'vehicle/stream/audio'

-> ?

'_game.dat151' files in 'vehicle/stream/audio'

-> ?

difference of'.datxx', '.datxx.rel' & '.datxx.nametable'

-> ?


#
### meta files

'carcols.meta' in 'vehicle/stream/'

-> collision behavior of the vehicle

'carvariations.meta' in 'vehicle/stream/'

-> differences between models (important for vehicle packs)

'handling.meta' in 'vehicle/stream/'

-> handling behavior of the vehicle

'vehicleweapons.meta' in 'vehicle/stream/'

-> weapons on the vehicle

'vehicles.meta' in 'vehicle/stream/'

-> ?

'vehiclelayouts.meta' in 'vehicle/stream/'

-> ?

'caraddoncontentunlocks.meta' in 'vehicle/stream/'

-> ?

'dlctext.meta' in 'vehicle/stream/'

-> ? (only '.meta' not mentioned in 'stream.cfg')

