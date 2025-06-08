---
layout: default
title: Diagnostic port
permalink: /diagnostic_port
nav_order: 2
---

# Diagnostic port

A diagnostic port is a physical connector in the car that allows us to connect to vehicle elecronic systems and communicate with them.

Every BMW built since 1988 includes a dedicated diagnostic connector for communication with the car's electronic systems. Over the years, the type and location of this connector have evolved.

BMW models manufactured between 1988 and 2000 typically feature a 20-pin circular diagnostic connector with a pie-shaped notch in the center. You'll find this connector located in the engine compartment.

Starting in 1996, BMW began integrating the OBD2 (On-Board Diagnostics II) connector into vehicles destined for the North American market. This rectangular 16-pin connector became standard for emissions-related diagnostics.
By July 2000, BMW had fully transitioned, removing the older round diagnostic connectors. From this point forward, all diagnostic capabilities are provided exclusively through the OBD2 connector, which is typically located inside the cabin, often under the dashboard.

## BMW OBD-II Adapters

| Name        | Target   |
| ----------- | -------- |
| K+DCAN      |          |
| ENET        | DIY      |
| ICOM Next A | Official |
| ICOM Next B | Official |
| ICOM Next D | Official |
| ISSS Next   |          |

### PC-Car Connection

This is a summary on how to physically connect your PC to your car.

First, locate where your car OBD II port may be placed. You can check out your _Owner's Handbook for Vehicle_ and search for the _OBD_ or _Socket for on-board diagnosis_ terms.
You can find more about how the port may look like in <https://en.wikipedia.org/wiki/On-board_diagnostics#OBD-II_diagnostic_connector>.

#### ENET

The ENET cable has two ends. One connects to the OBD II port in your car and the other one into an Ethernet port in your PC. If you are using a laptop without ethernet port you may consider purchasing an Ethernet USB adapter.
