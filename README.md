watchtv
=======

is a script to watch and record live HDTV streams.

This script is based on watchteleboy (see: https://github.com/reduzent/watchteleboy)
and uses a very similar frontend.

The sources are hosted at github: http://github.com/jadoe/watchtv

Copyright: 2015		Jane Doe
           2010-2015	Roman Haefeli

License:   GPL-2 


Requirements
------------

 * avconv
   is used for recording or caching for playback (allows play'n'pause
   and seeking in live streams).
   You may find it packaged as 'libav-tools' in your distro's repos.
   
 * mpv or mplayer
   both work, though mpv is preferred and has priority if both
   commands are found. Used to play the streams.

 * wget


Usage
-----

Do `watchtv --help` to get a quick summary of options. For playback mode,
you do:
  
 `watchtv [--channel "CHANNEL NAME"]`

For recording, you do:

 `watchtv --record [--other-options ARGS]`


Bugs
----
  
If you find some or if you have a feature request, post them to the author:

  Jane Doe <jane.doe@openmailbox.org>

or open an issue on the project's issue tracker on github.com:

  https://github.com/jadoe/watchtv


ENJOY! -jD
