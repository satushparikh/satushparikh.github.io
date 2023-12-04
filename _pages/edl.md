---
layout: archive
title: "EDL-EEG"
permalink: /projects/edl/
author_profile: true
redirect_from:
  - /edl
  - /project/edl
---

Course project for EE344: Electronic Design Lab, Spring 2023  
*with Aditya Sriram, Shivam Patel, Anubhav Bhatla, Ankith R, Nithish Reddy*  
  
[GitHub](https://github.com/Aayush2003/EEG-Data-Acquisition-System){: .btn--code}  [YouTube](https://www.youtube.com/watch?v=h8a7uUWLfgk){: .btn--youtube}  

![PCB Top Layer](/images/EDL_PCB.jpg)

EEG (Electroencephalography) is a non-invasive method of capturing brain signals. These signals are captured using a 3D-printed headgear equipped with electrodes for EEG data acquisition. The electrodes transmit data to a circuit responsible for processing these signals and forward them to a laptop for displaying.  

Based on an extensive study of component datasheets and operating procedures, we designed the entire circuit by making appropriate choices for devices, drawing up the circuit schematics, writing appropriate software for handling and processing received data, and designing, fabricating, and testing the PCB. As a part of the project, we designed two PCBs:

* A 24-electrode channel 4-layer PCB (pictured above) equipped with an analog front-end, 6 daisy-chained analog-to-digital convertors, and a microprocessor chip, capable of transmitting final data through UART, Wi-Fi, or local storage on an SD card.  
* A modular PCB for demonstration purposes, capable of acquiring 4-electrode channels of data using a single analog-to-digital convertor and appropriate analog front-end. The modular PCB performs peripheral interfacing with a microprocessor which displays the acquired signals on a laptop.  

To demonstrate the working of our design, we used the modular PCB to acquire EEG data for actions such as blinking, responses to visual stimuli, and resting alpha rhythm in the brain. Our final demonstration can be viewed in the above video on YouTube. Due to our exemplary performance throughout the duration of the course, our team was among those awarded the Best Project Award.
