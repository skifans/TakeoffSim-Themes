# TakeoffSim-Themes
All the themes TakeoffSim has in it's official repository. Want to add a theme? PR

##Details
All HTML files, or files otherwise not contained in the resources folder are released under the GPL v2.0
###All files in /resources are released under their own respective licenses, and are labeled as such.

##Rules/Internals
TakeoffSim uses Pebble internally. You can read more about Pebble's specification here: http://www.mitchellbosecke.com/pebble/documentation

No trying to exploit this for security holes. TakeoffSim's GUI is robustly fortified, and trying to exploit the GUI will cause the program to crash, the theme to be deleted, and a flag reported to TakeoffSim.

##Requirements
Any extra themes must implement validation. JavaScript is acceptable, and JavaScript can be assumed to be available. It may require an Internet connection, but that is not prefer red, and must be labeled as Internet only. Lastly, all data that gets sent via the default theme must also be sent from the custom theme, or the program will not run.