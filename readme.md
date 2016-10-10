Athame
======

Introduction
------------
Athame is a program for downloading music from music streaming and sharing services.
It is intended for educational and private use only, and **not** as a tool for pirating and distributing music.
Above all else, remember that the artists and studios put a lot of work into making music -- if you can, purchase
music directly from the artist as more money goes to them.

Usage
-----
Enter a URL in the "URL" textbox, then click "Add". It will show up in the download queue. Click "Start" to begin downloading.

Currently, Athame only supports Tidal and Google Play Music URLs. This will eventually be upgraded to a generic plugin
interface, and the Google Play Music and Tidal services will be in different repositories.

If you haven't signed in, you can click the `Menu` button, then go to `Settings` and choose the tab of the music service
you want to sign into. You can also just enter a URL and click "Click here to sign in" on the error message below the URL
textbox.

Under `Settings > General`, you can change where music is downloaded to as well as the filename format used. There is an explanation
of the valid format specifiers on the General tab.

TODO
----
* Implement a plugin API.
* Add an option to execute an external program (like `ffmpeg`) after each track or collection download.
* Properly implement cancellation and stopping on sign in and download.
* Implement search.