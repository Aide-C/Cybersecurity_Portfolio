# Identify the Attack Vectors of a USB Drive
In this activity, I assessed the attack vectors of a USB drive. I considered a scenario of finding a USB drive in a parking lot from both the perspective of an attacker and a target.

USBs, or flash drives, are commonly used for storing and transporting data. However, some characteristics of these small, convenient devices can also introduce security risks. 
Threat actors frequently use USBs to deliver malicious software, damage other hardware, or even take control of devices. 
USB baiting is an attack in which a threat actor strategically leaves a malware USB stick for an employee to find and install to unknowingly infect a network. 
It relies on curious people to plug in an unfamiliar flash drive that they find.

The scenario: 
I am a part of the security team at Rhetorical Hospital and arrive to work one morning. On the ground of the parking lot, I found a USB stick with the hospital's logo printed on it.
There’s no one else around who might have dropped it, so I decided to pick it up out of curiosity.
I brought the USB drive back to my office where the team has virtualization software installed on a workstation. 
Virtualization software can be used for this very purpose because it’s one of the only ways to safely investigate an unfamiliar USB stick. 
The software works by running a simulated instance of the computer on the same workstation. 
This simulation isn’t connected to other files or networks, so the USB drive can’t affect other systems if it happens to be infected with malicious software.

I created a virtual environment and plug the USB drive into the workstation. The contents of the device appear to belong to Jorge Bailey, the human resource manager at Rhetorical Hospital.
Jorge's drive contains a mix of personal and work-related files. For example, it contains folders that appear to store family and pet photos. There is also a new hire letter and an employee shift schedule.
