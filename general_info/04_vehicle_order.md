---
layout: default
title: Vehicle Order
permalink: /general_info/vehicle_order
parent: General information
nav_order: 4
---

# Vehicle Order (VO)

The Vehicle Order (VO), or Fahrzeugbestellung (FA) in German, is a value programmed into a vehicle that encodes the vehicle model, VIN and option list with wich a BMW left the factory.

This value is also backed up in BMW servers and dealerships can check if it matches the one in the car via the Aftersales Online System (AOS).

The Vehicle Order value is comprised of different sections described below.

## Zeitkriterium / VO Date / Production Date

Vehicle Order value includes a production date code. This code affects different configuration values in car units that may change the behaviour or appearance of your car.

## SALAPA List

The word SALAPA is an acronym of the German words _Sonderausstattung_, _Ladenausstattung_ and _Paket Ausstattung_. Those translate to something similar to _Special Equipment_, _Country Equipment_ and _Package Equipment_.

The Vehicle Order contains a list of SALAPA elements. Each SALAPA element represents a piece of physical equipement present in a car, a particular software to be run in different car units (ECUs) and also a set of configuration options for different car units.

There is an small selection of possible SALAPA element codes below.

| Reference | Code | Name                                                                 | Description                                             |
| --------- | ---- | -------------------------------------------------------------------- | ------------------------------------------------------- |
| S1CAA     | 1CA  | Selection CoP relevant vehicles                                      | May be internal BMW _Conformity of Production_ related. |
| S1CBA     | 1CB  | CO2 equipment                                                        |                                                         |
| S1CCA     | 1CC  | Automatic start/stop function                                        |                                                         |
| S1CDA     | 1CD  | Brake energy regeneration                                            |                                                         |
| S230A     | 230  | EU specific additional equipment                                     |                                                         |
| S255A     | 255  | Sport leather steering wheel                                         |                                                         |
| S258A     | 258  | Runflat tyres                                                        | Tyres capable of circulating up to 80Km/h punctured.    |
| S2DBA     | 2DB  | 17" light alloy wheels star spoke 327                                |                                                         |
| S320A     | 320  | Deletion of model designation                                        | No model numbers in the back.                           |
| S386A     | 386  | Roof rails                                                           |                                                         |
| S3APA     | 3AP  | Windscreen with grey shade band                                      |                                                         |
| S423A     | 423  | Floor mats in velour                                                 |                                                         |
| S428A     | 428  | Warning triangle                                                     |                                                         |
| S431A     | 431  | Interior rear view mirror with automatic anti-dazzle                 |                                                         |
| S441A     | 441  | Smokers package                                                      |                                                         |
| S4ATA     | 4AT  | Interior trim finishers with black high-gloss                        |                                                         |
| S502A     | 502  | Headlight washer system                                              |                                                         |
| S508A     | 508  | Park distance control (PDC)                                          |                                                         |
| S522A     | 522  | Xenon light                                                          |                                                         |
| S548A     | 548  | Speedometer with kilometer reading                                   |                                                         |
| S575A     | 575  | Additional 12v power socket                                          |                                                         |
| S609A     | 609  | Navigation system professional                                       |                                                         |
| S612A     | 612  | BMW assist                                                           |                                                         |
| S614A     | 614  | Internet preparation                                                 |                                                         |
| S615A     | 615  | Extended BMW online information                                      |                                                         |
| S616A     | 616  | BMW online                                                           |                                                         |
| S620A     | 620  | Voice control                                                        |                                                         |
| S633A     | 633  | Business mobile phone preparation with Bluetooth                     |                                                         |
| S698A     | 698  | Area code 2 for DVD                                                  |                                                         |
| S6AAA     | 6AA  | BMW teleservices                                                     |                                                         |
| S6ABA     | 6AB  | Control BMW teleservices                                             |                                                         |
| S6FLA     | 6FL  | Usb audio interface                                                  |                                                         |
| S6VCA     | 6VC  | Combox controller                                                    |                                                         |
| S7SPA     | 7SP  | Navigation system professional with mobile preparation for Bluetooth |                                                         |
| L801A     | 801  | German national version                                              |                                                         |
| L819A     | 819  | Spanish national version                                             |                                                         |
| S851A     | 851  | German language version                                              |                                                         |
| S879A     | 879  | German on-board documentation                                        |                                                         |
|           | 8KA  | Oil service interval 30.000 Km / 24 months                           |                                                         |
| S8TFA     | 8TF  | Active pedestrians safety                                            |                                                         |
|           | 8TL  | Daytime lights front and rear active                                 |                                                         |
|           | 8TN  | Daytime driving lights selectable                                    |                                                         |
|           | 8V1  | NCAP label                                                           |                                                         |
