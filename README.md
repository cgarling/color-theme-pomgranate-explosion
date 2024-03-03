color-theme-pomgranate-explosion
================================

A soft and elegant color theme for GNU Emacs.

Usage
-----

This is a fork of the original "Pomgranate Explosion" color theme by [Benoit Marcot](https://github.com/bmarcot/color-theme-pomgranate-explosion) which is updated to work with the new [color-theme-modern](https://github.com/emacs-jp/replace-colorthemes) plugin. It is recommended to install color-theme-modern through [MELPA](https://melpa.org/#/getting-started). Once you have cloned color-theme-pomgranate-explosion with `git clone https://github.com/cgarling/color-theme-pomgranate-explosion.git`, be sure to add the following lines to your `.emacs` or `init.el` config file, replacing the install location as appropriate.

```
(package-install 'color-theme-modern)
(require 'color-theme-modern)
(load-file "<INSTALL LOCATION>/color-theme-pomgranate-explosion.el")
(enable-theme 'pomgranate-explosion)
```

About the colors
----------------

The colors come from the excellent Kuler's color theme [Pomgranate Explosion](http://kuler.adobe.com/#themeID/1923981) by _draghia_.


Screenshot
----------

![Pomgranate Explosion screenshot](https://github.com/bmarcot/color-theme-pomgranate-explosion/raw/master/misc/pomexplo_screen.png)

Licence
-------

Copyright © 2012 Benoît Marcot

Copyright © 2024 Christopher Garling

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.
