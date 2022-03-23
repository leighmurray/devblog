Beat Game
=========

Beat Game is a VR Music game.

There will be two builds for this game. One is the map maker and one is the actual game. The bulk of the work will be done with the map maker.

* Map maker

The map maker is used to create and preview all the maps. In the MVC framework it will be able to toggle between and Editor Viewer and a Gameplay Viewer.

** The Editor viewer will be able to CRUD the track data whereas the Gameplay viewer will use the exact same viewer as the actual game.  This is why there needs to be
a clear separation for the Models, Views and Controllers.

It consists of the following components.

* Track Data

