<img align="right" width="64px" src="https://raw.githubusercontent.com/hauke96/GeoNotes/main/app/src/main/res/mipmap-xxxhdpi/ic_launcher.png">

# GeoNotes
A simple app to create and manage georeferenced notes (text and photos) on a map. The goal is to create the notes as fast as possible without any unnecessary UI/UX overhead.

<p align="center">
<img src="screenshots.png" alt="GeoNotes Screenshots"/>
</p>

## Download

[<img src="https://fdroid.gitlab.io/artwork/badge/get-it-on.png" alt="Get it on F-Droid" height="60">](https://f-droid.org/packages/de.hauke_stieler.geonotes/)
[<img src="https://user-images.githubusercontent.com/663460/26973090-f8fdc986-4d14-11e7-995a-e7c5e79ed925.png" alt="Download APK from GitHub" height="60">](https://github.com/hauke96/geonotes/releases/latest)

Runs on Android 4.1 and newer.

## Need help?

See the [OSM Wiki page](https://wiki.openstreetmap.org/wiki/GeoNotes) for detailed descriptions about all the features.

## Features

* Create, move and delete notes
* Attach photos to note
* List of all notes
* Export all notes in GeoJson format
* Show and follow current location

## Use-case and Philosophy

This is the basic use-case of this app:

* Take notes while being outside (maybe even while walking or sitting in a bus)

To enable this, the app follows some basic principles:

* **Simplicity:** Make creating, editing, moving and deleting of notes as fast/easy as possible
* **No upload** of data and no creation of notes on osm.org
* **General purpose:** No restriction in the content of a note
* **Not a note management tool:** No import, no high level management operations
* **Simple and pragmatic UI:** No unnecessary animations, no overloaded UIs
* **Feature toggles:** The possibility to enable/disable features

Features that will *not* make it into GeoNotes:

* Offline maps: Too much work (where does the data come from? What format? When to update the data? Vector or raster data/tiles? etc.)
* Creating notes on osm.org
* Directly editing data
* All sorts of features that will only be used by ~5% (meaning a very small amount) of the users
* iOS support

Use other apps like [StreetComplete](https://github.com/streetcomplete/StreetComplete) if you want to directly edit OSM data or to create notes on osm.org.

