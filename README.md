zam-plugins
===========

Collection of LV2/LADSPA audio plugins for high quality processing

Note:

The .dsp.cpp files cannot be fully regenerated by faust because faust 
does not generate enough metadata when building ladspa plugins.
Until then, this package uses manually overriden .dsp.cpp files.

However, I have provided the .dsp files in the sources for archiving or
if anyone wants to play with the source, and for the future when faust 
handles metadata better..


Build Dependencies:
===================

	pkg-config lv2-dev ladspa-sdk lv2-c++-tools faust


Installation:
=============

	make submodules
	make
	sudo make install


Package Maintainers:
====================

	make submodules
	make dist
