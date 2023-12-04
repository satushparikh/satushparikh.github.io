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
  
[GitHub](https://github.com/Aayush2003/EEG-Data-Acquisition-System){: .btn--code}  

![PCB Top Layer](/images/EDL_PCB.jpg)

EEG (Electroencephalography) is a non-invasive method of capturing brain signals. These signals are captured using a 3D-printed headgear equipped with electrodes for EEG data acquisition. The electrodes transmit data to a circuit responsible for processing these signals and forward them to a laptop for displaying.  

We designed the entire circuit reponsible for acquiring the EEG data by making appropriate choices for component devices, drawing up the circuit schematics, writing appropriate software for handling and processing received data, and designing, fabricating, and testing the PCB. As a part of the project, we designed two PCBs:

* A 24-electrode channel PCB (pictured above) equipped with analog front-end, 6 analog-to-digital convertors, and a microprocessor chip, capable of transmitting final data through UART, Wi-Fi, or local storage on an SD card.  
* A modular PCB for demonstration purposes, capable of acquiring 4-electrode channels of data using a single analog-to-digital convertor and appropriate analog front-end. The modular PCB performes peripheral interfacing with a microprocessor which displays the acquired signals on a laptop.  

To demonstrate the working of our design, we used the modular PCB to acquire EEG data for actions such as blinking, responses to visual stimuli, and resting alpha rhythym in the brain. Our final demonstration can be viewed in the above video on YouTube. 