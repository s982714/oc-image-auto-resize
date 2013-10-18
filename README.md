# OpenCart Image Auto-Resize #

Remove whitespace on OpenCart thumbnail and get the best image result as on this [article at OpencartNews](http://www.opencartnews.com/tutorials/auto-type-opencart-image-resize/)

**Download:** [All release](https://github.com/qahar/oc-image-auto-resize/releases)

**Required:** [vQmod](https://code.google.com/p/vqmod/downloads/list) <br/>
**Tested on:** 1.5.5.x and 1.5.6


### Installation ###
1. Copy folder **vqmod/** inside the upload/ folder to your site.
2. Clear your image cache **image/cache/data/**


### Tips ###

1. **Scale image from top center instead of vertical and horizontaly center.** <br/>
Assume you use v.1.5.6, open system\library\image.php and comment line 93<br/>
//$ypos = (int)(($height – $new_height) / 2);


### License ###

Copyright (C) 2013  A. Qahar Mudzakkir

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
