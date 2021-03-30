# Filament sensor USB

This plugin reacts to Triangle Labs filament runout sensor (microswitch) connected to a USB serial capable Teensy© (I used 3.2) or Arduino© which has been programmed with the contents of [FIRMWARE REPO HERE].
I selected this sensor because they can be daisy chained together for multi-filament setups.
If triggered it issues configured command to printer.

Let's check some features:
* pop-up notification when printer runs out of filament
* very handy pop-up when printer requires user input while changing filament
* filament check at the start of the print - if no filament present it won't start printing, again pop-up will appear
* filament check at the end of filament change - just to be sure you won't start printing with no filament
* check if printer supports M600 when printer connected and gcode starts with M600 - if not user will be notified through pop-up
* info pop-up when plugin hasn't been configured
* filament runouts can be repeatable which didn't work with other plugins I tried
* user-friendly and easy to configure
* handles delibrate M600 filament change
* runs on OctoPrint 1.3.0 and higher

**NOTE: this plugin won't work if you use OctoPrint only to start printing from printer internal SD card**

## Setup

Install via the bundled [Plugin Manager](https://docs.octoprint.org/en/master/bundledplugins/pluginmanager.html)
or manually using this URL:

    https://github.com/dmattox10/Filament_sensor_USB/archive/master.zip

## Configuration

TODO

#### Advice

TODO

## Screenshots

TODO
