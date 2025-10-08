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
# Objective/Background
The goal of this competition was to create a payload for the Georgia Tech Rambling Rockets Club. We decided on modyfing a open-source cosmic ray detector for our project. This would have measured the point at which cosmic rays decay into Muons in the atmosphere.
# Mechanism of operation
The detector works by having a plastic scintillator, this would create a photon which would be detected by a photomultiplier, before being amplified by a custom circuit to be detected by the ESP32 logger.
# Design
The design used COTS components for the main brain and sensors that detected launch and supplied power. Most of the devices would communicate on a I2C line for easier programming and wiring. 
