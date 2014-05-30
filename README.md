Deezmaker-slicing-profiles
==========================

Slicing profiles for the Bukobot and Bukito 3D printers

These profiles use firmware retraction by default, and are intended for use with Bukobot firmware from https://github.com/whosawhatsis/Marlin. If the "Last Updated" date that you see when connecting to your machine is before 2014-04-27, you should update it to work with these profiles. 

The Cura profiles are imported using "File > Open Profile" within Cura, and the Slic3r profiles are imported using the new "File > Load Config Bundle" option within Slic3r 1.1+.

These profiles use firmware-controlled retraction to achieve better control of nozzle pressure, so retraction is configured in the custom start gcode sections of the profiles, and the rest of the slicer's own settings are ignored.
