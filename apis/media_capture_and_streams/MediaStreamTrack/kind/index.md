---
title: 'kind'
notes:
  - 'Needs example, spec reference'
readiness: 'In Progress'
relationships:
  applies_to:
    predicate: 'Property of '
    value: apis/media_capture_and_streams/MediaStreamTrack
    href: /apis/media_capture_and_streams/MediaStreamTrack
  return:
    predicate: 'Returns an object of type '
    value: String
    href: /apis/media_capture_and_streams/MediaStreamTrack
standardization_status: 'W3C Working Draft'
summary: 'Returns the string &quot;audio&quot; if the object represents an audio track or &quot;video&quot; if object represents a video track.'
tags:
  - API_Object_Properties
  - API
  - Media_Capture_and_Streams
  - Needs_Examples
uri: 'apis/media capture and streams/MediaStreamTrack/kind'

---
## Summary

Returns the string &quot;audio&quot; if the object represents an audio track or &quot;video&quot; if object represents a video track.

Property of [apis/media\_capture\_and\_streams/MediaStreamTrack](/apis/media_capture_and_streams/MediaStreamTrack)[apis/media\_capture\_and\_streams/MediaStreamTrack](/apis/media_capture_and_streams/MediaStreamTrack)

## Syntax

**Note**: This property is read-only.

``` js
var result = track.kind;
```

## Return Value

Returns an object of type StringString

