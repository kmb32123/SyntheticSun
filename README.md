SyntheticSun
============

Python script to precisely control grow light fixtures according to your current locations sunrise and sunset in order to accurately simulate [photoperiodism](http://en.wikipedia.org/wiki/Photoperiodism#In_plants). This means that your plants will recieve a different amount of daylight each day just like they would with natural light. Also this is a justification for me to use a raspberry pi to control grow lights rather than a $5 timer.


As of right now everything is hardcoded to my location, Platteville WI. If anyone wanted to make it customizable via command-line options and [argparse](https://docs.python.org/3.2/library/argparse.html) I would happily merge it in. Also including geocoding via [The Google Geocoding API](https://developers.google.com/maps/documentation/geocoding/) would be a significant usabiltiy improvement. I attempted to use [pygeocoder](http://code.xster.net/pygeocoder/wiki/Home) and [geopy] (https://github.com/geopy/geopy) but unfortunately they both have setup issue on my system when I use pip. Not sure the issue there...