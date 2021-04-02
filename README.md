## What is this?
This gives an example for how to add add-on vehicles as a resource to
your alt:V server. This of course gives an overview as detailed as possible.

## Overview
"How to Setup" might seem a bit difficult


## How to Setup
1. Copy the "vehicle" folder into your "resources" folder
('.../altv-server/resources/'). 
2. Rename it to anything you want (ex.: MANUFACTURER_MODEL).
3. Delete every example '.meta', which was not included in the add-on vehicle
you are adding.
4. Copy-Paste every '.meta' file from your add-on vehicle into 'vehicle/stream'.
5. Delete every example '.yft' and '.ytd' file 'vehicle/stream/assets/assets'
6. Copy-Paste every '.yft' and 'ytd' files from your add-on vehicle, which are
most likely named like the vehicle is named (filled in mostly into 'NAME' in
this repository), into 'vehicle/stream/assets/assets'.
7. Delete every example '.yft' file in 'vehicle/stream/assets/mods'.
8. Copy-Paste every '.yft' file which you did not used in step 5 into
'vehicle/stream/assets/mods'.

## Description
# main files and tuning
'vehicle/stream/assets/assets' ->
'.yft' files in 'vehicle/stream/assets/mods' ->
'awc' files in 'vehicle/stream/audio/sfx/dlc_NAME'
->
'.dat[...]' files in 'vehicle/stream/audio'
->

'.meta' files' in 'vehicle/stream/'
->
