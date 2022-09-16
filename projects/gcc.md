---
layout: project
type: project
image: img/adc/gcc.png
title: "Analog to Digital Converter"
date: 2021
published: true
labels:
  - Controller Modification
  - Microcontroller
  - Falstad
summary: "Simulating installing an analog to digital converter inside a Gamecube controller for a final project in EE 326."
---

<img class="img-fluid" src="img/adc/gcc.png">

Implementing an analog to digital converter (ADC) into a Gamecube controller was a final team project for EE 326, Fall 2021. The ADC was simulated using a cicuit simulation [Falstad](https://www.falstad.com/circuit/). The objective of this project was to modify a Gamecube controller in order for the triggers to be converted from analog to digital. The reasoning for this was because of a certain game *Super Smash Brothers Ultimate* where the triggers are used to shield oncoming attacks. Other controller's triggers are read digitally meaning that the shield comes out instantly and have an advantage over Gamecube controllers. So the remedy was to implement an ADC into the microcontroller,specifically the triggers, in order to remove any unfair advantages.

<img class="img-fluid" src="/img/adc/shields.png">
<img class="img-fluid" src="/img/adc/lranalog.png">

The extent of this project wasn't to actually build something but to simulate it. Simulating was done by first contructing a basic ADC schematic and then modifying it to suit our project. In this case, implementing NMOSes was done to mimic a controller input from a user.

<img align="middle" src="/img/adc/adc.png">
<img align="right" src="/img/adc/nmosimp.png">

In this project I gained experience with simulating circuits and adding more components to an existing circuit. I also experienced using NMOSes as switches, which was a topic we had just learned in that class only a few months prior.
