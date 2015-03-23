Weather
=======

![Version](https://img.shields.io/badge/version-1.0-green.svg)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](http://opensource.org/licenses/MIT)

Overview
--------

Spend a lot of time at the command line?  Want to know what it would feel like to be outside?  If so then this is the script for you!

Weather is a bash scipt that uses API's from [hostip.info](http://www.hostip.info/) and [Yahoo](http://developer.yahoo.com/everything.html) to determine your current location and provide the relavant weather information.

Installation
------------

1. Place the weather script in your PATH.
2. Ensure weather is executable.

Usage
-----

    weather [-u c|f] [-w id] [-n name]

      -h, --help           Display usage information.
      -u, --units [c|f]    Set units to celsius or fahrenheit.
      -w, --woeid [id]     Set location by where on earth id (WOEID).
      -n, --name  [name]   Set location by place name.

Show weather for your current location:

    weather

Show weather for another location:

    weather -n Tokyo

Change the units to celcius:

    weather -u c

Gotchas
-------

Locations cannot always be determined by [hostip.info](http://www.hostip.info/).  If this is the case for your IP, you can visit [hostip.info](http://www.hostip.info/), click on the link that says "Make a correction" and add your location.

License
-------

MIT is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
