**Candelabra** is a browser-based time tracker capable of tracking time on
multiple projects and providing for quick switching between which timer
is running.

![screenshot](https://raw.github.com/jtauber/candelabra/master/screenshot.png)

It is a single HTML file (using hosted versions of jQuery)
that uses localStorage for persisting logs between browser refreshes but
it is not intended for long-running time recording. The expected use case
is that times would be logged to some other system occasionally and cleared
from Candelabra.

You can run it directly from http://jtauber.github.com/candelabra/candelabra.html

For maximum enjoyment, make your browser as narrow as possible and turn off
as much chrome as you can (toolbar, status bar, etc).

**NOTE**: time resolution is in minutes so don't expect the timer to change
until a minute has passed.

As of version 0.2, Candelabra has been tested on Safari, Chrome and Firefox.

## Authors

- James Tauber
- Luke Hatcher

## Change Log

### 0.1

- initial release

### 0.2

- removed external Bootstrap dependency
- added gradient to project block
- fixed scrolling issues when projects extend too far
- added support for mobile devices
- added iOS application mode when saved to home screen

