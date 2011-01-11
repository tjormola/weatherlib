                              Lua weather library

   This library can be used to do some weather related routines and solar
   calculations in Lua. Also provides unit conversion routines.

                                  Downloading

   Weather library home page is at
   [1]http://solitudo.net/software/lua/weatherlib/ and it can be
   downloaded from the public Git repository at
   git://scm.solitudo.net/weatherlib.git. Gitweb interface is available at
   [2]http://scm.solitudo.net/gitweb/public/weatherlib.git.

   Remember to download the submodules after cloning weatherlib.git.
    1. $ git submodule init
    2. $ git submodule update

                                  Installation

   Install the src/weatherlib.lua under some of the directories included
   in the default LUA_PATH for your Lua distribution, or install under
   desired location and set LUA_PATH accordingly. More info about LUA_PATH
   at [3]http://www.lua.org/pil/8.1.html.

                               API Documentation

   API documentation for weatherlib is available under the api/ directory
   of the distribution.

                            Copyright and licensing

   Copyright: © 2010 Tuomas Jormola [4]tj@solitudo.net
   [5]http://solitudo.net

   Licensed under the terms of the [6]GNU General Public License Version
   2.0. License terms are included in the file COPYING.

   This module derives code from libgweather library which is part of the
   [7]GNOME project. libgweather is available at
   [8]http://ftp.gnome.org/pub/GNOME/sources/libgweather/ and it is
   licensed under the terms of the [9]GNU General Public License Version
   2.0

   This module derives code from the [10]NOAA Solar Calculator. Original
   JavaScript code at the aforementioned site is placed under public
   domain.

References

   1. http://solitudo.net/software/lua/weatherlib/
   2. http://scm.solitudo.net/gitweb/public/weatherlib.git
   3. http://www.lua.org/pil/8.1.html
   4. mailto:tj@solitudo.net
   5. http://solitudo.net/
   6. http://www.gnu.org/licenses/gpl-2.0.html
   7. http://www.gnome.org/
   8. http://ftp.gnome.org/pub/GNOME/sources/libgweather/
   9. http://www.gnu.org/licenses/gpl-2.0.html
  10. http://www.esrl.noaa.gov/gmd/grad/solcalc/
