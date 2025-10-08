---
layout: post
title: GT Student Launch
description:  A Cosmic ray detector designed to be launched on a collegiate student launch rocket, using open source electronics. This was not assembled due to scheduling issues.
skills: 
- CNC machining
- Onshape
- Project Leadership
- KiCad
- ESP32
- PCB design
main-image: /image.png
---
## Objective / Background
The goal of this project was to design a payload for the Georgia Tech Rambling Rockets Club in the NASA Student Launch competition. Our team decided to modify the Cosmic Watch open-source cosmic ray detector to measure the altitude where cosmic rays decay into muons in the atmosphere. The project explored how small, low-cost detectors could collect scientific data during a rocket launch.
##  Mechanism of Operation
The payload was based on the Cosmic Watch Muon Detector, which uses a plastic scintillator to produce photons when hit by cosmic rays. These photons are detected by a silicon photomultiplier (SiPM), then amplified by a custom circuit and recorded by an ESP32-based microcontroller. The entire system ran on battery power to operate independently during flight.
## Design
The design used Commercial Off-The-Shelf (COTS) parts to simplify construction and improve reliability. All sensors and electronics communicated over an I²C line, and the structure was made entirely from aluminum for strength and light weight.
Although the payload was not built because our team leader was unavailable for the next meeting, the project gave me experience in electronics integration, sensor design, and scientific data collection systems.
