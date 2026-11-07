# FreeSource

by the Doom Cross Port Collab team (C) 2024-2026

## What This Is

Simple set of freely licensed resources for use in idTech1 engine games, primarily for Boom-derived Doom source ports.


## Before You Build This Project

This project may need some local properties filled in by whoever clones this project.
Make a `doommake.properties` file and look at the properties in `PROPS.txt` for the
modifiable settings for this project. The `doommake.properties` file that you create should
NOT BE CHECKED IN TO YOUR REPOSITORY!


## To Build This Project


This project requires the [DoomTools](https://github.com/MTrop/DoomTools) toolchain for
building it. Clone this project to a new folder and type:

	doommake init


...In order to ensure everything has been prepped correctly (some directories or files
may need extracting, downloading, or copying).

To both initialize and build this project and its distributable archive:

	doommake


To clean the build folder, type:

	doommake clean


To build a resource WAD suitable for editing your project in the build folder, type:

	doommake editor


To build all components:

	doommake all


To build the full release:

	doommake release
