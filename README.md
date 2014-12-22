Pebble Super Fonts - Demo App
=============================

This demo app is based off the [app_font_browser] sample app and has been expanded to include many custom fonts and different text messages in each font.


Usage
-----

Initially you are presented with a menu of different font options.  The up and down buttons navigate the list.  Pressing back will exit the app and pressing the select button will show you a demo page.

On the demo page you can press select to cycle through the available text messages to see how they are presented in the font.  The up and down buttons switch to the previous and next fonts.  The back button returns you to the menu.

That's all there is to it.


How To Compile
--------------

Clone this repository on GitHub.  Then fire up [CloudPebble] and import this project from GitHub.  Open the source file `app_font_browser.c` and then press the green button to compile and send this to your phone.  Make sure you have the developer channel enabled on your phone and ideally it will get sent to your pebble within moments.


About the Fonts
---------------

These fonts have been hand selected for a variety of purposes.  Some are good digital watch faces, others are great for larger text and still more are good for smaller text.


### [Anonymous Pro](http://www.marksimonson.com/fonts/view/anonymous-pro) by Mark Simonson

A very clean monospaced font.  Designed with coding in mind.  Released under the Open Font License version 1.1 ([OFL]).


### [Digit](http://www.dafont.com/digit.font) by paldave

Digital clock based font with readable letters.  Monospaced.  Source cites "100% Free".


### [Noticia Text](http://www.fontsquirrel.com/fonts/noticia-text) by José Miguel Solé

Readable font designed for print and black & white applications.  Released under the Open Font License version 1.1 ([OFL]).


### [Open Sans Condensed](https://www.google.com/fonts/specimen/Open+Sans+Condensed) by Steve Matteson

Designed with an upright stress, open forms and a neutral, yet friendly appearance.  Optimized for print, web, and mobile interfaces with excellent legibility characteristics in its letterforms.  Released under the Apache License version 2.0 ([APACHE]).


### [Pendule Ornamental](http://fontstruct.com/fontstructions/show/pendule_ornamental) by Scott Lawrence

This specialized ornamental/display font has been created explicitly for use in a digital clock. Two different styles of digits are provided with as A-P and a-p. The digits 0-9, and A-F, as seen on LCD and LED displays are included, along with colon(:), decimal(.) point, and negative sign (-).  Released under the Creative Commons Attribution-ShareALike 3.0 License ([CC-ASL]).


### [Phonebook](http://www.1001freefonts.com/phonebook.font) by Manfred Klein

Slightly heavier and condensed to fit more words horizontally.  License according to sources all cite it is free.  Font is not listed on Klein's [official site](http://manfred-klein.ina-mar.com/), but all of his other fonts request that a donation is made when used for commercial use.


### [Segment 7](http://openfontlibrary.org/en/font/segment7) by Cedric Knight

Strictly seven-segment (plus point) calculator display face, fixed-width and free. Other LED/LCD digital fonts may kern or include paths that are not available with seven segments in order to represent characters better. Segment7 does the best it can for upper- and lower-case Latin without compromising on the true LED display appearance.  Released under Open Font License version 1.1 ([OFL]).


### [Source Sans Pro](https://github.com/adobe-fonts/source-sans-pro) by Paul D. Hunt

This is a sans serif typeface intended to work well in user interfaces.  Simplified glyph designs were based off Gothic fonts and additional details were added to easily distinguish letters.  Reads well for short strings and extended settings.  Released under the Open Font License version 1.1 ([OFL]).


License Information
-------------------

The original example was listed under the MIT license.  This one is licensed under the same.  See [LICENSE.md](LICENSE.md) for the full text.

Fonts are licensed under multiple licenses.  For convenience, each font cites their license and here is the text of every license used:

* Apache License version 2 - [APACHE]
* Creative Commons Attribution-ShareALike License version 3.0 - [CC-ASL]
* Open Font License version 1.1 - [OFL]


[APACHE]: APACHE.md
[app_font_browser]: https://github.com/pebble/pebble-sdk-examples/tree/master/watchapps/app_font_browser
[CC-ASL]: CC-ASL.md
[CloudPebble]: https://cloudpebble.net/
[OFL]: OFL.md