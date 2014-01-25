Charterish Small Caps.
======================

Nothing new, just the small caps from [Charis
SIL](http://scripts.sil.org/charissilfont), with vertical metrics matching
those of the freely available Charter font from Bitstream. I also quickly
cooked some text figures from the default ones.

Building installable font files
-------------------------------

Run `make`. You should see green stuff and some "OK" messages.
The build process requires FontForge with python scripting support,
`ttfautohint`, `sfnt2woff` (from the `woff-tools` package on Ubuntu) and
`ttf2eot`, for example from [this
repository](https://github.com/harrastia/ttf2eot).

`make install` will install the TTF fonts into your local `.fonts/` directory 
and update the font cache.
