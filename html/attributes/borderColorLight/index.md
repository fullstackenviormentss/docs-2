---
title: 'borderColorLight'
attributions:
  - 'Microsoft Developer Network: [[Windows Internet Explorer API reference](http://msdn.microsoft.com/en-us/library/ie/hh828809%28v=vs.85%29.aspx) Article]'
compatibility:
  feature: borderColorLight
  topic: html
notes:
  - 'Review import; Remove MS bias; Update/improve example; Update descriptions; Fix lists & compatibility info'
readiness: 'Not Ready'
summary: 'Sets the colors of the upper and left corners of the cell. Used with borderColorDark to set the lighter colors in an element''s shaded border. Deprecated in HTML4, unsupported in HTML5. Use CSS.'
tags:
  - Markup_Attributes
  - HTML
  - Needs_Examples
uri: html/attributes/borderColorLight

---
## Summary

Sets the colors of the upper and left corners of the cell. Used with borderColorDark to set the lighter colors in an element's shaded border. Deprecated in HTML4, unsupported in HTML5. Use CSS.

<table class="wikitable">
<tr>
<th>
Applies to

</th>
<td>
 ?

</td>
</tr>
</table>
## Notes

### Remarks

This property is the opposite of [**borderColorDark**](/html/attributes/borderColorDark) and must be used with the [**border**](/html/attributes/border) property that corresponds to the **BORDER** attribute. This property does not affect the Cascading Style Sheets (CSS) [**border**](/css/properties/border) composite properties. Some client applications do not recognize color names, but all client applications should recognize RGB color values and display them correctly. This property is no longer recommended. Use the [**borderColor**](/css/properties/border-color) property instead.

### Syntax

## See also

### Related pages

-   table[table](/html/elements/table)
-   `td`
-   `th`
-   `tr`
