## My own changes
1. Changed the size of the `canvas_wrapper` element to zero because it was interfering with selection even when canvas was not displayed.
2. Changed the resize function so it doesn't keep continously increasing the width and height of the canvas element.
3. Changed the location of the buttons to the bottom-right corner.
4. Added keyboard shortcuts via `eventListener` for all three buttons.
    1. `'` for Toggle Visibility.
    2. `,` for undo.
    3. `.` for clean whiteboard.
5. Made the canvas element have a crosshair cursor.

# Anki-TouchScreen
Touch screen functionality for Anki

Implements same drawing/writing mechanism as in AnkiDroid. Your writing is NOT intended to remain on the cards after review - same as in AnkiDroid.

Use the menu `View` → `TouchScreen` to activate/change settings.

Use <kbd>Ctrl</kbd> + <kbd>R</kbd> to toggle the touchscreen.

Use icons which will show up in the top right corner of the review screen to temporarily hide/clean the board.
Enjoy!

Warning: the version for Anki 2.0 has limited functionality, and may sometimes not work as expected; since the release of Anki 2.1, the old version is not supported.


#### Changelog:
- 0.2.6 - make "undo" action available under <kbd>Alt</kbd> + <kbd>Z</kbd>
- 0.2.4 - add support for enhanced image occlusion, add a fix for "a double click bug" by LaucianK 
- 0.2.3 - bug fix release, improvements to undo button, styling and performance
- 0.2.1 - minor fix for the buttons/canvas positioning
- 0.2 - added "undo" option, improved the support of long cards plus other minor improvements

#### Disclaimer
Important parts of Javascript code were inspired by <a href="http://creativejs.com/tutorials/painting-with-pixels/index.html" rel="nofollow">creativejs tutorial</a>. I recommend you check out the resource if you are interested in learning JS.

This add-on works well with <a href="https://ankiweb.net/shared/info/1496166067">Anki Night Mode</a>.

#### For developers
You are more than welcome to contribute! While I may not be able to support every user of this addon, I will do my best to help any developer willing to open PR implementing new features or fixing bugs.
