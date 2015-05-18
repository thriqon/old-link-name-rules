OldLinkNameRules
================

Reverts udev rules renaming `eth0` to something like `enp2s0` by shadowing the corresponding rules file (with a `touch`).

Reasoning
---------

I have an Arch package containing the configurations for the Wifi networks I use. To make it usable accross different computers it is important to have a consistent naming scheme.
The old system (`eth0` and `wlan0`) does this, the new system does not.

License
-------

Since there is not much source around (none, actually, it's just an empty file), a license is overkill. The PKGBUILD however may be redistributed under the terms of the GPL.

