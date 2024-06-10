# Shower HTML presentation engine Fork with Mouse Navigation 

Forked from [Shower Presentation Template](https://github.com/shower/shower) [archive](http://shwr.me/shower.zip).

Uses Web Component to create navigation.
## Structure
`js/nav.js` - main file. Creates navigation component and puts it in the end of body. So you don't have to change `html`.

`css/nav.css` - outer styles to position navigation. Includes classes to change position. Bottom center is default. Add one of the classes to body (shower class) to change it.

Also some changes are done to `shower.js` (for mousewheel and bug fix) and theme font files (bug fix).

## How to use
Just link `js` and `css` files to your shower pres html file. And use this copy of `shower.js` for other fixes/features. Should work with both themes.

## Features
* On screen buttons for next/prev/all slides you can click with mouse
* Change slides with mousewheel

## Fixes
* Slides count kept going when press 'next' on last slide (so it took multiple 'back' presses)
* Old font files in ribbon theme put console error. Just downloaded new one from Google Fonts.

## Report bugs
Please report only fork problems in Issues here. Please make sure the problem does NOT occur in original shower first.