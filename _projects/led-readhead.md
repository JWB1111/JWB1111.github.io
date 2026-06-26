---
layout: project
title: LED Optical Readhead
subtitle: Optical sensor for pulse detection using LED technology for Data Transmission with Galvanic Isolation
category: Embedded Systems · Optics
skills:
  - Circuit Design
  - C++
  - Signal Processing
  - Analog Electronics
specs:
  - key: Project Type
    value: Work related
  - key: Domain
    value: Embedded Systems, Optics, Data Transmission
  - key: Status
    value: Completed
  - key: Tools Used
    value: "[KiCad, soldering iron, PuTTy, oscilloscope]"
---

## Motivation

<!-- Describe why you built this. What problem did it solve? What interested you about it? -->

There was a need to read out values from a fully produced device to confirm that production values are correctly set. Due to the nature of the project having high security standards a direkt connection to the motherboard via header is not possible.

## Design Approach

<!-- Explain your thinking: what were the key design decisions? -->

The PCB layout and first circuit were given to me by the hardware developement. There were two options. One of them was a litte bit more complex the other one simpler but less robust an needed more work to find the operatig point. In the end the decision fell in favor of the simper circuit due to almost same reliailty at a lower cost.

## Implementation

<!-- Walk through how you built it, step by step -->


## Challenges & Solutions

<!-- What went wrong? What did you learn? This is the most interesting part for recruiters. -->

The resistor R1 was used to set the operating point for the phototransistors. This proved more challenging than expected. Since the software and hardware development worked simultaniopusly it sometimes happend that you found a good srtting with the oscilloscope but when reading out the values via puTTy issues occured. So it went back to the lap, trying to improve 

## Results

<!-- What did the final device achieve? Any measurements, demos, photos? -->

[Describe the outcome — does it work? What did you measure? What would you do differently?]
