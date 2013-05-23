{{Page_Title|text-decoration-line}}
{{Flags
|Checked_Out=Yes
}}
{{Standardization_Status|W3C Working Draft}}
{{API_Name}}
{{Summary_Section|The text-decoration-line CSS property sets what kind of line decorations are added to an element.}}
{{CSS Property
|Initial value=none
|Applies to=All elements
|Inherited=No
|Media=visual
|Computed value=as specified
|Animatable=No
|Values={{CSS Property Value
|Data Type=none
|Description=Produces no text decoration.
}}{{CSS Property Value
|Data Type=underline
|Description=Each line of text is underlined.
}}{{CSS Property Value
|Data Type=overline
|Description=Each line of text has a line above it.
}}{{CSS Property Value
|Data Type=line-through
|Description=Each line of text has a line through the middle.
}}{{CSS Property Value
|Data Type=-moz-anchor-decoration
|Description=Mozilla CSS Extension, not suitable for web content.
}}
}}
{{Examples_Section
|Not_required=No
|Examples={{Single Example
|Language=HTML
|Code=<p>This has no none</p>
<p>This is underlined</p>
<p>This is overlined</p>
<p>This has a line-through</p>
|LiveURL=http://cdpn.io/EtyDp
}}{{Single Example
|Language=CSS
|Code=p:nth-child(1) { text-decoration: none; }
p:nth-child(2) { text-decoration: underline; }
p:nth-child(3) { text-decoration: overline; }
p:nth-child(4) { text-decoration: line-through; }
|LiveURL=http://cdpn.io/EtyDp
}}
}}
{{Notes_Section}}
{{Related_Specifications_Section
|Specifications={{Related Specification
|Name=CSS Text-decoration Level 3
|URL=http://www.w3.org/TR/css-text-decor-3/
|Status=Working Draft
}}
}}
{{Compatibility_Section
|Not_required=No
|Imported_tables={{Imported Compatibility Table}}
|Desktop_rows={{Compatibility Table Desktop Row
|Chrome_supported=Unknown
|Chrome_version=
|Chrome_prefixed_supported=Unknown
|Chrome_prefixed_version=
|Firefox_supported=Unknown
|Firefox_version=
|Firefox_prefixed_supported=Yes
|Firefox_prefixed_version=6.0
|Internet_explorer_supported=Unknown
|Internet_explorer_version=
|Internet_explorer_prefixed_supported=Unknown
|Internet_explorer_prefixed_version=
|Opera_supported=Unknown
|Opera_version=
|Opera_prefixed_supported=Unknown
|Opera_prefixed_version=
|Safari_supported=Unknown
|Safari_version=
|Safari_prefixed_supported=Unknown
|Safari_prefixed_version=
}}
|Mobile_rows={{Compatibility Table Mobile Row
|Android_supported=Unknown
|Android_version=
|Android_prefixed_supported=Unknown
|Android_prefixed_version=
|Blackberry_supported=Unknown
|Blackberry_version=
|Blackberry_prefixed_supported=Unknown
|Blackberry_prefixed_version=
|Chrome_mobile_supported=Unknown
|Chrome_mobile_version=
|Chrome_mobile_prefixed_supported=Unknown
|Chrome_mobile_prefixed_version=
|Firefox_mobile_supported=Unknown
|Firefox_mobile_version=
|Firefox_mobile_prefixed_supported=Yes
|Firefox_mobile_prefixed_version=6.0
|IE_mobile_supported=Unknown
|IE_mobile_version=
|IE_mobile_prefixed_supported=Unknown
|IE_mobile_prefixed_version=
|Opera_mobile_supported=Unknown
|Opera_mobile_version=
|Opera_mobile_prefixed_supported=Unknown
|Opera_mobile_prefixed_version=
|Opera_mini_supported=Unknown
|Opera_mini_version=
|Opera_mini_prefixed_supported=Unknown
|Opera_mini_prefixed_version=
|Safari_mobile_supported=Unknown
|Safari_mobile_version=
|Safari_mobile_prefixed_supported=Unknown
|Safari_mobile_prefixed_version=
}}
|Notes_rows=
}}
{{See_Also_Section
|Topic_clusters=Text
}}
{{Topics|CSS}}
{{External_Attribution
|Is_CC-BY-SA=No
|Sources=MDN
|MDN_link=https://developer.mozilla.org/en-US/docs/Web/CSS/text-decoration-line
|MSDN_link=
|HTML5Rocks_link=
}}