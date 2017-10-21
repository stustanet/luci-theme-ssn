SSN theme for LuCI (LEDE/OpenWRT)
========================================

The SSN theme is an alternative HTML5 theme for LuCI based on the
[darkmatter theme](https://github.com/apollo-ng/luci-theme-darkmatter) which
has evolved from luci-theme-bootstrap & luci-theme-material, in an attempt to
bring a more concise, clean and visually pleasing UX to LEDE/OpenWRT.


Installation
------------

Edit the feeds.conf and add the following to it:

    # luci-ssn
    src-git luci-ssn git://gitlab.stusta.de/stustanet/luci-ssn.git.git

Update your build environment and install the package:

    $ scripts/feeds update luci-ssn
    $ scripts/feeds install luci-ssn
    $ make menuconfig

Go to LuCI -> Themes, select luci-ssn, exit, save and build as usual.

Enable the Theme
----------------

  * Go to System -> System -> Language and Style
  * Choose SSN in the Design selectbox

License
-------

This program is free software; you can redistribute it and/or
modify it under the terms of the GNU General Public License
as published by the Free Software Foundation; either version 2
of the License, or (at your option) any later version.
