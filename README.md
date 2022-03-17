SMM KiCad Library
=================

contents
--------

### Symbols

* Adafruit Metro Mini
* I40115 5V regulator
* ID-12LA
* SMM Mega Shield Connector
* TPIC6A595NE power shift register


### Footprints

* ID-12LA
* Adafruit Metro Mini
* Various SMM logo sizes
* I50115 5V regulator
* SMM standard terminal blocks

setup
-----

Clone or download this repository anywhere you'd like (somewhere **permanent**), and then open KiCad.
Go to `Preferences > Manage Symbol Libraries` and under "Global Libraries", click the "+" button. Enter the nickname "SMM" and under the library path add the full path to the `SMM.lib` file in this library. Click "OK". 

Now click `Preferences > Manage Footprint Libraries` and under "Global Libraries", click the "+" button. Give it the nickname "SMM" and set the library path as the full path to the `SMM.pretty` directory in this library. Click "OK".

Done!
