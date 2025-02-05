---
title: v-ideographic
slug: Web/SVG/Attribute/v-ideographic
tags:
  - Deprecated
  - SVG
  - SVG Attribute
browser-compat: svg.elements.font-face.v-ideographic
---
{{SVGRef}}{{Deprecated_Header}}

The **`v-ideographic`** attribute indicates the alignment coordinate for {{Glossary("glyphs")}} to achieve ideographic {{Glossary("baseline")}} alignment for vertically oriented glyph layouts. The value is an offset in the font coordinate system relative to the glyph-specific {{SVGAttr("vert-origin-x")}} attribute.

You can use this attribute with the following SVG elements:

* {{SVGElement("font-face")}}

## Usage notes

<table class="properties">
  <tbody>
    <tr>
      <th scope="row">Value</th>
      <td>
        <code
          ><a href="/en-US/docs/Web/SVG/Content_type#number"
            >&#x3C;number></a
          ></code
        >
      </td>
    </tr>
    <tr>
      <th scope="row">Default value</th>
      <td><em>None</em></td>
    </tr>
    <tr>
      <th scope="row">Animatable</th>
      <td>No</td>
    </tr>
  </tbody>
</table>

* `<number>`
  * : This value indicates the alignment coordinate for the glyphs.

## Specifications

<table class="no-markdown">
  <thead>
    <tr>
      <th scope="col">Specification</th>
      <th scope="col">Status</th>
      <th scope="col">Comment</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        {{SpecName("SVG1.1", "fonts.html#FontFaceElementVertIdeographicAttribute", "v-ideographic")}}
      </td>
      <td>{{Spec2("SVG1.1")}}</td>
      <td>Initial definition</td>
    </tr>
  </tbody>
</table>

## Browser compatibility

{{Compat}}
