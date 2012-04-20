vsscripts
=========

A collection of miscellaneous build scripts

build.pl/BuildConsole.pm/BuildTimer.pm
======================================

A command line perl script to help out with building visual studio solutions:
* Supports using (and not using) Incredibuild
* Times builds
* Color codes output (warnings => yellow, errors => red)
* Regex-extracts warnings and errors to console window (CL, GCC, SNC)

setSingleProjectBuild.reg
=========================

Sets the max count of concurrent project builds preference to 1 (for easier log reading)