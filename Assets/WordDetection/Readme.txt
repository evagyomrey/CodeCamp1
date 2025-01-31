Word Detection
--------------


Authors
-------

They Love Games
http://theylovegames.com


Feedback
--------

Please post your feedback and feature requests in the forums:

http://forum.unity3d.com/threads/152178-Word-Detection-Verbal-Commands


Audience
--------

Anyone wanting to quickly add spoken words to their game play. Add word profiles at runtime and immediately

start detecting spoken words.


Compatibility
-------------

This project is targeted for Unity 4.5.1 or better.

iOS and Android device support can vary.


Hardware testing
----------------

(Android)

OUYA

Nexus 10

Samsung Galaxy S III

(iOS)

iPad 2nd Generation


What is in this package?
------------------------

This package includes a four example scenes in addition to the word detection package.


Example Scene 1 - Spectrum Mic, captures raw wave data from the microphone and performs

spectrum analysis which is rendered to a texture via the Graph Plotter.

Clicking on the example node in the scene reveals that the plot resolution can be altered

via a slider in the custom inspector.


Example Scene 2 - Array Copy, a tweak to the first example, capturing raw data from the

microphone is held in a circular array. This example reorders the array to keep the mic

position at the end of the array.


Example Scene 3 - Material Offset, rather than doing copy operations, this uses the material

texture offset to offset the mic position without needing to shift the array. The custom

inspector provides a toggle for normalizing the plot graph.


Example Scene 4 - Word Detection, words can be added at runtime which are detected and the

WordDetection's DetectedEvent fires each time the detected word changes. The detection

threshold can be tweaked via the custom inspector of WordDetection. Lower numbers are

more precise. Higher numbers are less precise.


Example Scene 5 - Verbal Control, words can control the transformation of a cube


Example Scene 6 - Push to talk in order to issue commands


Example Scene 7 - Mechanim example uses Word Detection to change states


Example Scene 8 - Adds saving and loading profiles to file with a dialog


Example Scene 9 - Adds word navigation using word sets


Example Scene 10 - Adds verbal commands that control facial expressions


Example Scene 11 - Verbal commands control another hi-resolution head


Example Scene 12 - Verbal command control a low-resolution talking head


Example Scene 13 - Verbal commands control another low-res talking head


Example Scene 14 - Verbal commands control blend shapes


Example Scene 15 - Verbal commands control emotional states


Example Scene 16 - Verbal commands control goat media clip playback


Example Scene 17 - Verbal commands drive Character Controller input


Tutorials
---------

You will find detailed tutorial videos on our YouTube channel: http://www.youtube.com/playlist?list=PLEXfnMfl8Yrvr7ynEqdgYXrKzuAH5wtyf playlist.


Notes
-----

1. Add Spectrum Microphone to the scene via the menu GameObject->Create Other->Audio->Create Spectrum Microphone.

2. Add Word Detection to the scene via the menu GameObject->Create Other->Audio->Add Word Detection.

3. Custom inspectors are available to tweak both Spectrum Microphone and Word Detection game objects.


Change Log
----------

1.0 - Added a realtime spectrum microphone. Added audio word detection.

1.1 - Added Example5 verbal control demo

1.2 - Rewrote FFT library

1.3 - Downgraded to Unity 3.5.0

1.4 - Added example 6

1.5 - Added support for profile loading and saving. Added an example toggle for "Use Plotter" which disables example texture rendering when off.

1.6 - Added push to talk example

1.7 - Added mechanim example

1.8 - Upgraded to Unity 4.5.1. Added file save dialog for word profiles, word set navigation, and the control of facial expressions with word commands

1.9 - Added goat media clips with playback ties with word detection

1.10 - Word Detection can now drive a Character Controller

1.11 - Upgraded to Unity 5.1.2.
		Truncated some data files to reduce the core package size.
		Example data files can be downloaded from:
			https://github.com/tgraupmann/TAGENIGMA-Docs/blob/master/Word-Detection/Data/WordDetection_GoatMediaClips.unitypackage

Q & A
-----

You can send comments/questions to support@theylovegames.com where your feedback will help us create new tutorials and features

in order to improve the product.