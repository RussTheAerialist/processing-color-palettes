processing-color-palettes
=========================

A bunch of color palettes to use for processing sketches

To contribute, fork and submit a pull request.  Your color scheme should be
structured like this:

```
schemename/
  colors.pde -> Should define a color[] named "palette", and a string named "name"
  schemename.pde -> Symlink to ../color-viewer.pde
  schemename.png -> image that shows all of the colors, generated by color-viewer.pde
```
