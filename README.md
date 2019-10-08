# scalable_vector_graphics


SVG integrates with standards such as the DOM and XSL.
<h3> Advantages of SVG: </h3>
<ul>
  <li>
    Can be created and edited with any editor
  </li>
  <li>
    Can be searched, indexed, scripted, and compressed
  </li>
  <li>
    Are scalable and zoom-able
  </li>
  <li>
    Can be high quality printed at any resolution
  </li>
  <li>
    Doesn't lose quality if zoomed or resized
  </li>
  <li>
    Is an open standard
  </li>
  <li>
    Are pure XML
  </li>
  <li>
    Any element or attribute in SVG files can be animated.
  </li>

</ul>

<h3>Pro-Tips:</h3>
  <li>
    The **width** and **height** of the &#60;svg&#62; element refer to the whole SVG image
  </li>
  <li>
    SVG is XML, all elements need closed
  </li>
  <li>
    To style shapes use CSS
  </li>
  <li>
    Use fill-rule style with:
    * **even**,
    * **odd** or
    * **nonzero**
  </li>
  * All path commands can be expressed with either *lowercase* or *uppercase* with purpose
  * *lowercase* specifies *relative* positioning
  * *uppercase* specifies *absolute* positioning

<h3>Predefined Shapes</h3>
<table>
  <tr>
    <th>Name</th>
    <th>Tag</th>
    <th>Specific Attributes</th>
  </tr>
  <tr>
    <td>Rectangle</td>
    <td>&#60;rect&#62;</td>
    <td>
      **width:** horizontal length
      **height:** vertical length
    </td>
  </tr>
  <tr>
    <td>Circle</td>
    <td>&#60;circle&#62;</td>
    <td>
      **cx:** center x
      **cy:** center y
      **r:** radius
    </td>
  </tr>
  <tr>
    <td>Ellipse</td>
    <td>&#60;ellipse&#62;</td>
    <td>Extends Circle with
      **rx:** horizontal radius
      **ry:** vertical radius
    </td>
  </tr>
  <tr>
    <td>Line</td>
    <td>&#60;line&#62;</td>
    <td>
      **x1:** horizontal start position
      **y1:** vertical start position
      **x2:** horizontal end position
      **y2:** vertical end position
    </td>
  </tr>
  <tr>
    <td>Polyline</td>
    <td>&#60;polyline&#62;</td>
    <td>
      **points:** A space separated list of x,y coordinates
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
      **M:** moveto
      **L:** lineto
      **H:** horizontal lineto
      **V:** vertical lineto
      **C:** curveto
      **S:** smooth curveto
      **Q:** quadratic Bézier curve
      **T:** smooth quadratic Bézier curveto
      **A:** elliptical Arc
      **Z:** closepath
    </td>
  </tr>
  <tr>
    <td>Text</td>
    <td>&#60;text&#62;</td>
    <td>
      **x:** horizontal start position
      **y:** vertical start position
      **&#60;tspan&#60;:** a sub element for grouping lines of text
    </td>
  </tr>
</table>

# Filters
  * **&lt;feBlend&gt;:** filter for combining images
  * **&lt;feColorMatrix&gt;:** filter for color transforms
  * **&lt;feComponentTransfer&gt;:**
  * **&lt;feComposite&gt;:**
  * **&lt;feConvolveMatrix&gt;:**
  * **&lt;feDiffuseLighting&gt;:**
  * **&lt;feDisplacementMap&gt;:**
  * **&lt;feFlood&gt;:**
  * **&lt;feGaussianBlur&gt;:**
  * **&lt;feImage&gt;:**
  * **&lt;feMerge&gt;:**
  * **&lt;feMorphology&gt;:**
  * **&lt;feOffset&gt;:** filter for drop shadows
  * **&lt;feSpecularLighting&gt;:**
  * **&lt;feTile&gt;:**
  * **&lt;feTurbulence&gt;:**
  * **&lt;feDistantLight&gt;:** filter for lighting
  * **&lt;fePointLight&gt;:** filter for lighting
  * **&lt;feSpotLight&gt;:** filter for lighting
