# Scalable Vector Graphics
SVG integrates with standards such as the DOM and XSL.
<h3> Advantages of SVG: </h3>
<ul>
  <li> Can be created and edited with any editor </li>
  <li> Can be searched, indexed, scripted, and compressed </li>
  <li> Are scalable and zoom-able </li>
  <li> Can be high quality printed at any resolution </li>
  <li> Doesn't lose quality if zoomed or resized </li>
  <li> Is an open standard </li>
  <li> Are pure XML </li>
  <li> Any element or attribute can be animated. </li>
</ul>

<h3>Pro-Tips:</h3>
<ul>
  <li>
    The <code>width</code> and <code>height</code> html attributes of the &#60;svg&#62; element refer to the whole SVG image
  </li>
  <li> SVG is XML, all elements need closed </li>
  <li> To style shapes use CSS </li>
  <li>
    Use fill-rule style with:
    <ul>
      <li>even</li>
      <li>odd</li>
      <li>nonzero</li>
    </ul>
  </li>
  <li>
    All path commands can be expressed with different letter cases with a purpose of
    <ul>
      <li>lowercase specifing relative positioning</li>
      <li>uppercase specifies absolute positioning</li>
    </ul>
  </li>
</ul>

<h3>Predefined Shapes</h3>
<table>
  <thead>
    <th>Name</th>
    <th>Tag</th>
    <th>Specific Attributes</th>
  </thead>
  <tr>
    <td>Rectangle</td>
    <td>&#60;rect&#62;</td>
    <td>
      <ul>
        <li> width: horizontal length </li>
        <li> height: vertical length </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Circle</td>
    <td>&#60;circle&#62;</td>
    <td>
      <ul>
        <li> cx: center x </li>
        <li> cy: center y </li>
        <li> r: radius </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Ellipse</td>
    <td>&#60;ellipse&#62;</td>
    <td>
      Extends Circle with
      <ul>
        <li> rx: horizontal radius </li>
        <li> ry: vertical radius </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Line</td>
    <td>&#60;line&#62;</td>
    <td>
      <ul>
        <li> x1: horizontal start position </li>
        <li> y1: vertical start position </li>
        <li> x2: horizontal end position </li>
        <li> y2: vertical end position </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Polyline</td>
    <td>&#60;polyline&#62;</td>
    <td>
      <ul>
        <li> points: A space separated list of x,y coordinates </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Polygon</td>
    <td>&#60;polygon&#62;</td>
    <td>See *Polyline*</td>
  </tr>
  <tr>
    <td>Path</td>
    <td>&#60;path&#62;</td>
    <td>
      <ul>
        <li> M: moveto </li>
        <li> L: lineto </li>
        <li> H: horizontal lineto </li>
        <li> V: vertical lineto </li>
        <li> C: curveto </li>
        <li> S: smooth curveto </li>
        <li> Q: quadratic Bézier curve </li>
        <li> T: smooth quadratic Bézier curveto </li>
        <li> A: elliptical Arc </li>
        <li> Z: closepath </li>
      </ul>
    </td>
  </tr>
  <tr>
    <td>Text</td>
    <td>&#60;text&#62;</td>
    <td>
      <ul>
        <li> x: horizontal start position </li>
        <li> y: vertical start position </li>
        <li> &#60;tspan&#62;: child which groups lines </li>
      </ul>
    </td>
  </tr>
</table>

# Filters
<table>
  <thead>
    <th>Name</th>
    <th>Tag</th>
    <th>Use</th>
  </thead>
  <tbody>
    <tr>
      <td>Blend</td>
      <td>&lt;feBlend&gt;</td>
      <td>filter for combining images</td>
    </tr>
    <tr>
      <td>ColorMatrix</td>
      <td>&lt;feColorMatrix&gt;</td>
      <td>filter for color transforms</td>
    </tr>
    <tr>
      <td>ComponentTransfer</td>
      <td>&lt;feComponentTransfer&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Composite</td>
      <td>&lt;feComposite&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>ConvolveMatrix</td>
      <td>&lt;feConvolveMatrix&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>DiffuseLighting</td>
      <td>&lt;feDiffuseLighting&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>DisplacementMap</td>
      <td>&lt;feDisplacementMap&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Flood</td>
      <td>&lt;feFlood&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>GaussianBlur</td>
      <td>&lt;feGaussianBlur&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Image</td>
      <td>&lt;feImage&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Merge</td>
      <td>&lt;feMerge&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Morphology</td>
      <td>&lt;feMorphology&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Offset</td>
      <td>&lt;feOffset&gt;</td>
      <td>filter for drop shadows</td>
    </tr>
    <tr>
      <td>SpecularLighting</td>
      <td>&lt;feSpecularLighting&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Tile</td>
      <td>&lt;feTile&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>Turbulence</td>
      <td>&lt;feTurbulence&gt;</td>
      <td></td>
    </tr>
    <tr>
      <td>DistantLight</td>
      <td>&lt;feDistantLight&gt;</td>
      <td>filter for lighting</td>
    </tr>
    <tr>
      <td>PointLight</td>
      <td>&lt;fePointLight&gt;</td>
      <td>filter for lighting</td>
    </tr>
    <tr>
      <td>SpotLight</td>
      <td>&lt;feSpotLight&gt;</td>
      <td>filter for lighting</td>
    </tr>
  </tbody>
</table>
