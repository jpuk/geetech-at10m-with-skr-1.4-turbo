# geetech-at10m-with-skr-1.4-turbo
files relating to my upgraded geeetech a10m with skr 1.4 turbo and tmc2209 drivers

- 3d directory contains 3d models and stl files for parts I've made to upgrade the printer. 
	-Enclosure for the skr 1.4 and a seperate box for the power hotbed module and a buck converter to step the 24v down to 12v for the noctua fan.
	-Enclosure for the Big tree tech tft24 touch screen display.
	-Bracket to attach RGB LED strip to the printer using 25mm m5 bolts and two t-nuts.

- Marlin directory contains fork of Marlin with my custom configuration files for skr 1.4 turbo with tmc2209, sensorless homing on x and y, bl touch on z and neopixel led light strip.

- gta10m-extruder-wiring contains my reverse engineering of the wiring from the extruder module circuit board in the geeetech a10m so I could reuse the original cable loom for the hotend, fans and themistor. I've chosen to conect the BL touch directly rather than use the loom as the dupoint cables could come lose from the extruder module.
