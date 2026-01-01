vecx
====
* Forked from here: https://github.com/jhawthorn/vecx
* Just added a simple game selection rom file dialog
* from: http://tinyfiledialogs.sourceforge.net
* SPDX-License-Identifier: Zlib: https://en.wikipedia.org/wiki/Zlib_License
* Copyright (c) 2014 - 2024 Guillaume Vareille http://ysengrin.com
* git clone http://git.code.sf.net/p/tinyfiledialogs/code tinyfd
* Allow for bigger size compile (-DSIZEX2). See osint.c and Makefile

Requirements
------------
* `SDL2`
* `SDL2_image`
* `SDL2_gfx`
* Some external dialog programs. On Mac Sonoma it runs out of the box.
* On elementaryos8 I had to do a "sudo apt install zenity".

Usage
-----
* Buttons: asdf + cursor keys

DMG
---
* Compiled under Big Sur.
* Build App from information given here: https://stackoverflow.com/questions/1596945/building-osx-app-bundle
* and using this tool: https://github.com/auriamg/macdylibbundler
* DMG build with hdd tool from directory
* Runs also under Sonoma. Expected to run fom Big Sur upto ..
* vecx-HS.dmg compiled under High Sierra - rund from HS onwards ..
* vecx-Lion.dmg compiled under Lion - but since no dialog app for tinyfiledialog is found, you need to specify rom path!
  So for ex: rom/pinball.bin

Authors
-------
* Valavan Manohararajah - original author
* [John Hawthorn](https://twitter.com/jhawthorn) - SDL port
* [Nikita Zimin](https://twitter.com/nzeemin) - audio


Contributors
------------
* [Simon Rodriguez](https://twitter.com/simonkosua) - SDL2 port


