---
layout: activities
permalink: /subpages/rsms/
title: Remote Site Monitoring System (RSMS)
---
<br>
<br>
<center>
<img src="/images/remote.png" height="500" width="800">
</center>
<br>
<br>
<p class="headings">Introduction</p>

RSMS is a Raspberry Pi powered robotic camera arm. Its control system is based on remote access via SSH. The system can be adapted with a wide range of sensors other then/alongside it’s natural avatar of a remote-controlled camera arm. The system is designed to be integrated with “Scorpion” however the system is operable independently and may be used as it is. The dimensions of this machine are __x__x__ (Compacted) and the range is __x__x__. The machine is primarily fabricated using 3D printed parts (Material used: PLA).

<br>
<br>
<p class="headings">Purpose</p>

RSMS sees its application in a vast variety of use cases.  Ranging from simple site monitoring tasks such as a work area to post disaster rescue operations. Lots of kinds of sensor can be incorporated into this system. An example use case can be that we install a thermal camera on this system and send it away for fire rescue operations (of course after beefing up the construction to cope with hight temperatures by itself). This system can be adapted as an expansion of my project “Smruti” and “Scorpion”. 

<br>
<br>
<p class="headings">Current Status</p>
I plan to relay the servo control through an Arduino Nano (which in fact has hardware PWM) That will make the motion smooth. The Nano can take control instructions from RPi via pyfirmata. I also plan to make a proper UI for the video feed and control system along with proper encryption. The system currently relies on Wi-Fi/LAN Network for connecting with operator, however to extend the range of the system, we are looking into incorporating a JioFi 4G Router. Our custom made servo motors can be used to make the motion even more refined.


RSMS is a versatile robotic system has applications in diverse scenarios. Advanced features such using computer vision for detection of humans stranded in a post disaster situation etc. can be introduced, the RPi on board is capable of handling such tasks.

<p class="headings">Project Team</p>
- Jyothish Kumar J (Project Head)