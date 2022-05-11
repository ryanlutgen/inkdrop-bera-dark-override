# inkdrop-bera-dark-override
Very rough style override to customize Inkdrop's dark appearance

This is a brute force (through my looking at the DOM elements) override.

## FAQ

### Why seperate styles for Mac and Windows?

Though implementing this, I found that appearances were very inconsistent between the MacOS and Windows platforms, particularily with fonts.  Upon researching this a bit, I found that the two operating systems use different font renderers.  For instance, Menlo-Regular looks very nice on MacOS, but looks pixelated on Windows.  Avenir looks nice on MacOS, but looks much more **bold** on Windows.  Main deviation is that instead of those fonts, the Windows version uses Segoe UI.