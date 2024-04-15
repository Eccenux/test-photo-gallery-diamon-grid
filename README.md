# Diamon Grid Photo Gallery 

Gallery with animated, diamon shaped grid of photographs. Shows clip-path animation.

Demo page:
https://eccenux.github.io/test-photo-gallery-diamon-grid/

Explainer video:
https://www.youtube.com/watch?v=A5GXdjEOvos

## Notes

- clip-path animation is preatty picky about what it animates
  - Different number of points will not work.
  - Different number of curves will not work.
- Using Inkscape to build clip-path:
  - Be sure to set width of the document to desired width. **Warning**! Check properties to make sure the scale is **1** and size is in **px**.
  - Instead of rotating items use: menu _Object_ → _Transform_.
  - If you already rotated some items then remove "transform" attributes and do that again with menu _Object_ → _Transform_. You can also: [Remove transforms within Inkscape](https://stackoverflow.com/a/24180005/333296)
  - Avoid perfect aliginment as this might trigger inkscape optimization and remove curves (and animiation will not work).

## Copyright

CC0
