KORG padKontrol as Cubase Controller
====================================

Tested on Cubase 9 Artist, but quite possibly will work with other Cubase
versions new and old.

Instructions
------------

- Ensure padKontrol is plugged in via USB
- Load the scene file (padkontrol-editor-librarian-scene.kpks) into
  [padKontrol Editor Librarian](https://www.korg.com/us/support/download/software/0/161/1419/)
- Configure the MIDI for Librarian software to use padKontrol MIDI2
- Click "transmit" to load the configuration onto the device
- Open Cubase and access "Device Setup"
- From "Remote Devices" click the `+` icon and add a Generic Remote
- Set the MIDI in/out to the padKontrol MIDI2 port
- Click the "Import" button and load the map file (cubase9-generic-remote.xml)

The device should be working at this point. 

Transport/Commands Mapping
--------------------------

Here's how I have mapped the 4x4 grid (this can be modified to taste from
Cubase Device Setup):

| 	| 	| 	| 	|
|--------------------	|--------------------	|--------------------	|-----------------	|
| Markers Window     	| Previous Marker    	| Next Marker        	| Insert Marker   	|
| Workspace Number 1 	| Workspace Number 2 	| Workspace Number 3 	| Zoom to Project 	|
| Fast Rewind        	| Rewind             	| Forward            	| Fast Forward    	|
| Loop Region        	| Stop/Return        	| Start/Pause        	| Record          	|

Getting Fancy
-------------

As an optional step, I also included an icon map for printing onto
transparency paper. The icons were sourced from Google Images (not mine).

![Icons on the PadKontrol](https://github.com/unRARed/cubase-padkontrol/blob/master/icons-preview.jpg)

Happy Mixing!
