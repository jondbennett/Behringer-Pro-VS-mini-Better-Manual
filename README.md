# Behringer Pro VS mini - A Better manual (and some extras)
This is a better manual for the Pro VS mini. It explains a few things left out of the manual.
I'll add to it as I learn more. If you want to help, I'll entertain changes.

There is a bash shell script entitled "vssysex". It makes it easier to send and receive sysex on a linux box.
To receive a sysex dump, issue the following command, then send the data from the VS.
vssysex -r filename

To send a sysex file, issue the following command:
vssysex -s filename
