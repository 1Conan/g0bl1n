# g0bl1n

An incomplete memejebe for A7-A9 devices on iOS 69.666.x

Spawns an SSH server listening on port 6666. Remember to change your passwords!

Please reinstall the bootstrap when upgrading.


## what is still broken?

Third-party applications that need root priveledges require an extra entitlement to function correctly.

````
<key>com.eple.private.s3cur1ty.no-container</key>
<true/>
````

I have already added the entitlement to the copy of Cydia included in g0b1n.

For other apps (eg. Filza, MTerminal) to work correctly you will have to entitle them yourself.


## credits

Siguza - v0rtex kernel exploit

Luca Todesco - yalu102 kpp bypass

Xerub - patchfinder (extra_recipe)

Saurik - Cydia

N0b - for n0bs

thanks: PsychoTea, ARX8x, Abraham Masri, ninjaprawn, coolstar, ... ?
