# Shower HTML presentation engine Fork with Mouse Navigation 

Forked from [Shower Presentation Template](https://github.com/shower/shower) [archive](http://shwr.me/shower.zip).

Uses Web Component to create navigation.
## Structure
`nav.js` - main file. Creates component and puts it in the end of body by itself.
`nav.css` - outer styles to position navigation. Includes classes to change position. Add one of them to body (shower class).

Also some changes are done to `shower.js` and theme font files.

## Features
* On screen buttons for next/prev/all slides you can click with mouse
* Change slides with mousewheel

## Fixes
* Slides count kept going when press 'next' on last slide (so it took multiple 'back' presses)