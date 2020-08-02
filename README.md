# rtw2_registry

Repository for storing RTW2 patches and mods not hosted elsewhere. Structure and format heavily based on the [Aurora Registry](https://github.com/Aurora-Modders/AuroraRegistry) (which I played a role in developing), albeit simplified.

## Patches

Patches will be added to this repository as I have time and attention. Patch versions will be identified by Thellasic using string arithmetic.

## Mods

Mods will be defined by a simple `mod.json` format - see `mods/cv10_netherlands/mod.json` for an example. There is only one 'type' of mod, as only certain specific files can be altered in a vanilla installation of RTW2. `mod_locations.json` contains links to all known `mod.json` files - I'd encourage modders to leverage this file to host their own mods externally, although of course they're welcome to host mods within this repository as well.
