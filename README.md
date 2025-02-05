# SVG - Scalable Vector Graphics 

Eg:

    <svg width="50" height="50">
      <circle cx="25" cy="25" r="22" fill="blue" stroke="gray" stroke-width="2" />
    </svg>

### SVG Element
  SVG is text based image-format.Similar to **canvas** element.
  It's good to specify width and height of the SVG, else it can take size of its enclosing element.

### Simple Shapes
    <rect x="0" y="0" width="500" height="500" /> 
    <circle cx="250"  cy="25" r="25" /> //cx and cy are cordinates of the center, r - radius. This circle is centered in the middle of 500-pixel SVG.
    <ellipse cx="250" cy="25" rx="100" ry="25" /> //Ellipse need separate radius values for each axis.
    <line x1="0"  y1="0" x2="500" y2="50" stroke="black" />
    <text x="250" y="25" font-family="serif" font-size="25" fill="gray"> Easy-peasy</text>

### Styling SVG Elements
  fill
  stroke
  stroke-width
  opacity
  font-family(text)
  font-size(text)

### Layering
There is no layers in SVG. SVG does not support's CSS z-index, shapes can only within the two-dimensional x/y plane.

    
