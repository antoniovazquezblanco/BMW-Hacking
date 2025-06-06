---
layout: default
title: Diagnostic protocols
permalink: /diagnostic_protocols
---

# BMW Diagnostic Protocols

BWM diagnostic port in F-Series cars expose an ethernet connection.

BMW tools use a prococol called _HSFZ_ (_High Speed Fahrzeug Zugang_ or High Speed ​​Vehicle Access) to transmit and receive frames from the vehicle.

## HSFZ

You may find more information about this protocol in the following resources:

- <https://munich.dissec.to/kb/chapters/doip/doip.html>
- <https://www.wireshark.org/docs/dfref/h/hsfz.html>

Both Wireshark and Scapy support dissection of this protocol but Wireshark requires port configuration in preferences to be able to dissect the traffic.

There are ongoing efforst to improve protocol support in both tools. See:

- <https://github.com/secdev/scapy/pull/4760>
- <https://github.com/secdev/scapy/pull/4758>
- <https://github.com/secdev/scapy/pull/4757>
- <https://gitlab.com/wireshark/wireshark/-/merge_requests/20011>
