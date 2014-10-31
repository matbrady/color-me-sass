ColorMeSASSMap
===========

Colour library for SASS. Each color group has been coverted to a map to reduce the amount of global varaible scope. 

 [Full site with colours, variable names and documentation here](http://richbray.me/cms/).


Usage
------------------------------

###1. Setting Up

If your familiar with SASS or LESS this should be a walk in the park. Make sure the main `_color-me-sass.scss` file is imported at the very bottom so it will overwrite any similar colour variables you have.


###2. Using the Colours

There is a convience function ( `colorLib()` ) which allows easy lookup of each color by name. Or you can retrieve a color the old fashion way ( `map-get($colorLib, yellow)` ) 

	body {
		background-color: colorLib(yellow);
		color: colorLib(orangeDuller);
	}

The cool thing about CSS pre-processors is you can make the colour lighter or darker, desaturate or saturate colours, change the hue, or even mix two colours together and it will calculate the correct hexadecimal value and place it in the compiled CSS. Pretty neat right.



Liscense
------------------------------
Color Me SASS is licensed under the [☺ license.](http://licence.visualidiot.com/)

You, the licensee, are hereby granted free usage in both personal and commerical environments, without any obligation of attribution or payment (monetary or otherwise). The licensee is free to use, copy, modify, publish, distribute, sublicence, and/or merchandise the work, subject to the licensee inflecting a positive message unto someone. This includes (but is not limited to): smiling, being nice, saying “thank you”, assisting other persons, or any similar actions percolating the given concept.


The above copyright notice serves as a permissions notice also, and may optionally be included in copies or portions of the work.


The work is provided “as is”, without warranty or support, express or implied. The author(s) are not liable for any damages, misuse, or other claim, whether from or as a consequence of usage of the given work.

Changelog
------------------------------

**v 1.0**        Color Me SASS is born.

**v 1.1**        Added a few brand colours from [http://brandcolors.net/](http://brandcolors.net/) to the library

**v 1.2**        25/04/13 Added some colours from [preboot](http://getpreboot.com/#variables-colors)

**v 1.3**        04/06/13 Updated with over 90 dulux inspired colours
