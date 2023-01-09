---
layout: page
title: Projects
---

## ALTAIR: Energy-supervisor Architecture for Batteryless Applications


<img src="../assets/img/altair_pcb.png"
     alt="Prototype hardware"
     width="220"
     style="float: right;" />

Current energy-harvesting systems execute applications where tasks become logically dependent on the energy state of the storage. This approach of desigining applications is monolithic and limits scalability to new applications and power supply hardware. To address these limitations, we designed Altair energy-supervisor architecture to separate energy management from the application's main tasks. This decoupling makes energy-harvesting design easier, since now the power supply details and energy management decisions are abstracted from the applications. The energy-supervisor makes decision on behalf of the application, while ensuring different application requirements. Altair simplifies batteryless design by allowing modular and independent development of energy management and application.

Details: [ALTAIR (IPSN'22)]({{'/'|relative_url}}assets/papers/Paper1_saoda21altair.pdf)

## RetroIoT: IoT Device Reconfiguration using Battery Channel


<img src="../assets/img/retroiot.png"
     alt="Prototype hardware"
     width="220"
     style="float: right;" />

Once deployed, commercial IoT devices can hardly be upgraded to a new functionality due to closed-source hardware and software implementation. This signifies that the availability of better hardwares and advanced features regularly forces many devices to be obsolete. In the RetroIoT project, we demonstrated a new technique to upgrade an IoT device without modifying the device's hardware and software or desigining completely new devices. RetroIoT injects new sensor data or any metadata through the battery ports of the device and encodes the new data into the battery voltage readings transmitted by the sensor. RetroIoT's design is simple, low energy-overhead, and only requires access to battery voltage readings.

Details: [RetroIoT (MobiCom'22)]({{'/'|relative_url}}assets/papers/Paper2_saoda22retroiot.pdf)

## SolarWalk: Occupant Identification using Photovoltaic Harvesters

<img src="../assets/img/solarwalk.png"
     alt="Prototype hardware"
     width="220"
     style="float: right;" />

Identifying occupants in a smart space is key to many smart home control applications, yet, existing solutions have several limitations including high energy-overhead, special-purpose hardwares, and bulky installations. We proposed SolarWalk, a person identification system using small indoor photovoltaic (PV) energy harvesters that provides an ubiquituous source of power for many energy-harvesting sensors. Our observation is that the output voltage pattern of a PV cell is uniquely fluctuated when different persons walk by the cell, since the output voltage is directly proportional to the illuminance level at its surface. SolarWalk's identification technique demonstrates a repurposable and sustainable design point by using PV cells as a sensor.

Details: [SolarWalk (BuildSys'22)]({{'/'|relative_url}}assets/papers/Paper3_saoda22solarwalk.pdf)

## Hardware Artifacts


<!-- <p align="center">
     <img src="../assets/img/herald_pcb.jpg" width="100"/>
     <img src="../assets/img/altair_pcb.png" width="100"/>
     <img src="../assets/img/pascal.png" width="100" />
     <img src="../assets/img/digital_pcb.png" width="100"/>
</p> -->



| a) Herald (2.7x4.5cm) | b) Altair (6.8x6.3cm) | c) Pascal (2x4cm) | d) Polaris (4.3x2.3cm)|
|:-------------------------:|:-------------------------:|:-------------------------:| |:-------------------------:|
|<img width="400" alt="alt-text-1" src="../assets/img/herald_pcb.jpg"> |  <img width="400" alt="atl-text-2" src="../assets/img/altair_pcb.png"> |<img width="400" alt="alt-text-3" src="../assets/img/pascal.png">  | <img width="400" alt="alt-text-4" src="../assets/img/digital_pcb.png"> |
