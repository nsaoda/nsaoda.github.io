---
layout: page
title: Projects
---

## ALTAIR: Energy-supervisor Architecture for Batteryless Applications


<img src="../assets/img/altair_pcb.png"
     alt="Prototype hardware"
     width="220"
     style="float: right;" />

Current energy-harvesting systems execute applications where tasks become logically dependent on the energy state of the storage. This approach of desigining applications is monolithic and limits scalability to new applications and power supply hardware. To address these limitations, we designed Altair energy-supervisor architecture to separate energy management from the application's main tasks. This decoupling makes energy-harvesting design easier, since now the power supply details and energy management decisions are abstracted from the applications and new applications can benefit from this abstractions. The energy-supervisor makes decision on behalf of the application, while ensuring different application requirements. Altair simplifies batteryless design allowing modular and independent development of energy management and application.

Details: [ALTAIR (IPSN'22)]({{'/'|relative_url}}assets/papers/Paper1_saoda21altair.pdf)

## RetroIoT: IoT Device Reconfiguration using Battery Channel


<img src="../assets/img/retroiot.png"
     alt="Prototype hardware"
     width="220"
     style="float: right;" />

Once deployed, commercial IoT devices can hardly be upgraded to a new functionality due to closed-source hardware and software implementations. This signifies that the availability of better hardwares and advanced features regularly forces many devices to be obsolete. In the RetroIoT project, we demonstrated a new technique to upgrade a device without modifying the device's hardware and software or desigining completely new devices. Our approaches uses the battery ports of the IoT device to add a new sensor or metadata and the battery voltage readings in the sensor's transmitte data to encode the added data. RetroIoT's design is simple, low energy-overhead, and only requires access to battery voltage readings.

Details: [RetroIoT (MobiCom'22)]({{'/'|relative_url}}assets/papers/Paper2_saoda22retroiot.pdf)

## SolarWalk: Occupant Identification using Photovoltaic Harvesters

<img src="../assets/img/solarwalk.png"
     alt="Prototype hardware"
     width="220"
     style="float: right;" />

Once deployed, commercial IoT devices can hardly be upgraded to a new functionality due to closed-source hardware and software implementations. This signifies that the availability of better hardwares and advanced features regularly forces many devices to be obsolete. In the RetroIoT project, we demonstrated a new technique to upgrade a device without modifying the device's hardware and software or desigining completely new devices. Our approaches uses the battery ports of the IoT device to add a new sensor or metadata and the battery voltage readings in the sensor's transmitte data to encode the added data. RetroIoT's design is simple, low energy-overhead, and only requires access to battery voltage readings.

Details: [SolarWalk (BuildSys'22)]({{'/'|relative_url}}assets/papers/Paper3_saoda22solarwalk.pdf)
