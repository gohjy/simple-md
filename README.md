# simple-md
Simple Markdown editor and displayer.

## How to use
- **GitHub Pages**: [https://gohjy.github.io/simple-md](https://gohjy.github.io/simple-md)
- **Local**: Download `index.html` and open it in a browser. No local server or anything needed - just open the file. It's that simple.

## How it works
Grabs text box content, puts it through [zero-md](https://zerodevx.github.io/zero-md), does a bit of scroll hacks to make life slightly easier, and displays.

Checks for edits every second.

Very basic, expect it to break or not work properly.

## Extra stuff
The site will auto adjust to a horizontal or vertical layout based on the viewport siez.

Add `?horiz` to the end of the URL to force a horizontal (side by side) layout, or `?vert` to force a vertical (top and bottom) layout.

Add `?hidehelp` to the end of the URL to hide the "What's this?" link to this page.

## License
I honestly don't see the point in putting this under anything besides the [MIT License](https://choosealicense.com/licenses/mit/) 
(it's *one file* with *ridiculously simple code*), so that's what this repo's under.
*(zero-md is [licensed](https://github.com/zerodevx/zero-md?tab=ISC-1-ov-file#readme) under the [ISC License](https://choosealicense.com/licenses/isc/).)*
