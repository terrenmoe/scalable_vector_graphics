# scalable_vector_graphics

Any element or attribute in SVG files can be animated.

SVG integrates with standards such as the DOM and XSL.
  <h3> Advantages of SVG: </h3>
<ul>
  <li>
    can be created and edited with any text editor
  </li>
  <li>
    can be searched, indexed, scripted, and compressed
  </li>
  <li>
    are scalable and zoom-able
  </li>
  <li>
    can be high quality printed at any resolution
  </li>
  <li>
    don't lose quality if zoomed or resized
  </li>
  <li>
    is an open standard
  </li>
  <li>
    are pure XML
  </li>
</ul>

Pro-Tips:
  <li>
    The width and height of the <svg> element refer to the whole SVG image
  </li>
  <li>
    SVG is XML, all elements need closed
  </li>
  <li>
    To style shapes use css
  </li>
  <li>Use fill-rule style with evenodd|nonzero</li>

Predefined Shapes
<table>
  <tr>
    <th>Name</th>
    <th>Tag</th>
    <th>Specific Attributes</th>
  </tr>
  <tr>
    <td>Rectangle</td>
    <td><rect></td>
    <td>width height</td>
  </tr>
  <tr>
    <td> Circle </td>
    <td> <circle> </td>
    <td>
      <abbr title="center x">cx</abbr>
      <abbr title="center y">cy</abbr>
      <abbr title="radius">r</abbr>
    </td>
  </tr>
  <tr>
    <td> Ellipse </td>
    <td> <ellipse> </td>
    <td>
      Same as Circle plus
      <abbr title="radius x">rx</abbr>
      <abbr title="radius y">ry</abbr>
    </td>
  </tr>
  <tr>
    <td> Line </td>
    <td> <line> </td>
    <td> x1, y1, x2, y2 </td>
  </tr>
  <tr>
    <td>
    Polyline
    </td>
    <td>
    <polyline>
    </td>
    <td>
      <abbr title="A list of pairs of coordinate points">points</abbr>
    </td>
  </tr>
  <tr>
    <td> Polygon </td>
    <td> <polygon> </td>
    <td></td>
  </tr>
  <tr>
    <td> Path </td>
    <td> <path> </td>
    <td></td>
  </tr>
</table>
