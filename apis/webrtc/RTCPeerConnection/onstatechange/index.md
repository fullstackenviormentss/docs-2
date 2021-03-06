---
title: 'onstatechange'
notes:
  - 'Needs example, spec reference'
readiness: 'In Progress'
relationships:
  applies_to:
    predicate: 'Property of '
    value: apis/webrtc/RTCPeerConnection
    href: /apis/webrtc/RTCPeerConnection
standardization_status: 'W3C Working Draft'
summary: 'Handles the statechange event for when the readyState property is changed, i.e. with a call to setLocalDescription() or setRemoteDescription(). The event does not fire when a new RTCPeerConnection object is created.'
tags:
  - API_Object_Properties
  - API
  - WebRTC
  - Needs_Examples
uri: apis/webrtc/RTCPeerConnection/onstatechange

---
## Summary

Handles the statechange event for when the readyState property is changed, i.e. with a call to setLocalDescription() or setRemoteDescription(). The event does not fire when a new RTCPeerConnection object is created.

Property of [apis/webrtc/RTCPeerConnection](/apis/webrtc/RTCPeerConnection)[apis/webrtc/RTCPeerConnection](/apis/webrtc/RTCPeerConnection)

## Syntax

``` js
var result = element.onstatechange;
element.onstatechange = value;
```

